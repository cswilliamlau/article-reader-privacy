# Article Reader Privacy Policy

Last updated: October 5, 2026

This policy covers the Article Reader - Read Aloud Chrome extension, maintained
by the GitHub account cswilliamlau. The extension's purpose is to read web
articles or selected text aloud with an in-page player and sentence highlighting.

## Website content and speech

The extension accesses page content to identify article text, read selected text,
display playback controls, and highlight sentences. Article extraction and
highlighting take place in your browser. Article text and titles are held in
memory for the reading session, not saved as a reading history by the extension.
The developer does not operate a server that receives this content.

Text to be spoken is passed to the browser's Web Speech API and the selected
browser or operating-system voice. Some voices process speech locally. Online
voices, including some Google voices, may transmit text to their provider for
speech synthesis and require an internet connection. Their processing and
retention are governed by the provider's policies, not controlled by the
extension developer. Do not assume that all voices work offline or that
confidential text remains on your device when using an online voice.

## Preferences and temporary state

The extension saves your voice selection, playback speed, theme, and a voice
initialization flag in Chrome's extension sync storage. Chrome may synchronize
these preferences between browsers according to your Chrome account and sync
settings. Article text is not placed in sync storage by the extension.

Temporary tab identifiers and player visibility and autoplay flags are stored in
Chrome session storage to restore an open player after navigation. This is not
a stored list of browsing history and is not sent to the developer. Session
storage is temporary and is cleared by Chrome when the browser session ends or
the extension is unloaded.

## Analytics and data sharing

The extension does not include advertising trackers, analytics, or a developer
telemetry endpoint. It does not record a browsing-history log or send voice
choices, listening time, clicks, or article content to the developer for analysis.
No account with the developer is required to use the extension.

The developer does not sell user data, use or transfer it for advertising or
purposes unrelated to reading aloud, or use it to determine creditworthiness or
for lending. Text processing by a selected speech provider and preference
synchronization by Chrome are described above.

## Website access

The extension requests access to HTTP and HTTPS pages so it can read articles
across websites, display its player, highlight text, and restore an already-open
player after navigation. Its scripts are included in the extension package;
the extension does not download remote JavaScript for execution.

## Your choices

You can stop playback or close the player at any time. You can restrict website
access, disable the extension, or uninstall it through Chrome's extension
settings. Restricting access may prevent reading or automatic player restoration
on some websites. Closing or navigating away from a page ends its current
in-memory reading session; an open player may start a new session on the next
article. Stopping playback alone does not necessarily clear the loaded text.

You can change saved preferences in the player. Uninstalling the extension
removes its browser-managed extension storage from that Chrome installation.
Use Chrome's sync controls to manage synchronized data. For data processed by
an online speech provider, consult that provider's privacy controls and policy.

## Third-party services and support

Chrome, speech services, and GitHub operate under their own privacy policies:

- Google and Chrome: https://policies.google.com/privacy
- Apple, for applicable operating-system speech services: https://www.apple.com/legal/privacy/
- GitHub: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

For privacy questions, contact the maintainer through the project's GitHub
privacy and support repository: https://github.com/cswilliamlau/article-reader-privacy/issues

GitHub is separate from the extension. Information you voluntarily post there
may be public. Do not post confidential article text or personal information in
public reports.

## Policy changes

This policy will be updated when the extension's data practices change. The
date above identifies the latest revision. Any future analytics or additional
data processing would require updated disclosures and consent where applicable.
