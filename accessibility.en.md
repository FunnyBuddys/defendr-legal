# Accessibility statement

Version 2026-10-14 · effective 2026-10-14

The German version is authoritative. This English translation is provided for convenience.

## 1. What this covers

This statement applies to the website defendr.live, the personal area and the server administration at
app.defendr.live, and the status page status.defendr.live. We make it voluntarily. The Defendr bot itself runs inside
Discord; how accessible Discord's interface is lies with Discord.

## 2. Our goal and what the website does for it

The website should be usable by everyone. Our yardstick is the Web Content Accessibility Guidelines (WCAG) 2.2 at
level AA. We cannot say yet that the website meets every requirement of that level: the check with screen readers is
still to come (sections 3 and 4). What the website does today:

- You can operate the website with the keyboard. The first stop of the Tab key is the "Skip to content" link, and the
  element that has the focus is visibly marked.
- In a server's setup wizard, the website moves the focus to the heading of the new step whenever the step changes,
  also when you go back or forward with your browser's arrows.
- The pages are built on the server and can be read without JavaScript. One exception: a server's setup wizard needs
  JavaScript; without it, it shows a note with links to the settings pages.
- Text meets the contrast requirements, in the light and the dark colour scheme. States such as a severity, "On" or
  "Off" and a change not saved yet are not shown by colour alone, but also by a word or a symbol of their own.
- The website follows your device's "reduce motion" setting unless you explicitly choose full animations on the
  website. You can also reduce animations there yourself. Motion that plays by itself does not repeat and ends after
  a few seconds.
- Notices that disappear on their own wait while you point at them, while the focus is inside them or while the tab
  is in the background.
- At a width of 320 pixels, which is what a window 1280 pixels wide shows at 400 % zoom, you never have to scroll a
  page sideways.
- The website is available in eleven languages, Arabic with right-to-left reading direction. The charts of the server
  overview also contain a table with the same values, which screen readers read out.
- Before the website saves a change to a server's settings, it shows you what changes and waits for your
  confirmation. You can undo saved changes in the change history.

## 3. How we check

Automatic checks run before every new version of the website: the testing tool axe checks every page against the
rules of WCAG 2.0, 2.1 and 2.2 at levels A and AA, in the dark colour scheme in at least English, German and Arabic,
and every English page in the light colour scheme as well. In addition, every page is opened in English, German and
Arabic at a width of 320 pixels; none may need sideways scrolling. On top of that, automatic tests run individual
flows with the keyboard and without JavaScript, for example the settings of a server.

A check by hand with screen readers is planned: NVDA with Edge (German, Arabic) and VoiceOver on iOS (English). State
of this check: not yet carried out. This statement rests on our own assessment; no external body has checked the
website.

## 4. Known limitations

- The check with screen readers has not been carried out yet. So there may be barriers for people who use a screen
  reader that we do not know about yet. We will carry out the check and add its result to this statement.
- A server's setup wizard works only with JavaScript. Without JavaScript you reach the same settings through the
  settings pages.
- When you follow a link, your browser loads the new page in full. The website does not move the focus to the main
  heading of the new page; your browser starts as usual at the top of the page or at the place the link points to.
- Signing in happens on a page of Discord. We cannot influence its accessibility.
- Nine of the eleven languages are machine-translated; the pages say so. If a text is hard to understand, please tell
  us.
- The status page status.defendr.live is not part of the automatic checks of section 3.

## 5. Report a barrier

If you run into a barrier, write to us at contact@defendr.live or in the Discord support server
(https://discord.gg/vtPXf6t6jd). Please name the page and what did not work. We answer you, tell you whether and by when
we can fix the problem and, where possible, help you another way until then, for example through the same feature in
Discord.

## 6. Date of this statement

This statement was prepared on 2026-10-14 and is reviewed whenever the website changes significantly.
