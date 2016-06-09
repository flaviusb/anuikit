# anuikit
An ui kit - styling/layout/kerning parts, widget parts, display, window manager, made of tags. I feel that my desires are *quite* reasonable.

There is nothing here at the moment.

---

Parts:

Styling
- Stylesheets
- DOM + Shadow DOM selector things
- Tree rewriting/term rewriting
- Kerning/micro layout - TeX stuff
- Constraints
- Relationships between things
- Selectors, properties etc

Tags
- Custom components
- Structure and information
- Machine exposed - eg you can get the tags that a given window is made of

Document
- Similar to tags, but more emphasis on content and less on structure
- Machine exposed
- Concept of sources, bindings, etc

Chrome
- The visible manifestation of a user agent
- Window decoration, interactors etc.

Reflow/Responsive design

Hypertext
- Like HTML forms, but allows all levels/methods - eg full hypertext
- Transclusion?

Applications can be smushed together or taken apart, and can be treated as hypertext.

A display/interaction/sandbox layer, which is the 'user agent'?
Resources and URLs across some kind of socket.
A transport layer.
Protocol.
Mime types.

The protocol should do snowflaking and pipelining in part through conneg and something like extended mime-types. So options range from all in place in the document, through to 'associated resource push', keepalive + multiplexing + multifetch, just keepalive, to only get the named resource + connection close at the fully unsnowflaked end.
Note: ETags vs If-Modified-Since

Real text areas.

"Code on demand" eg Kropaya script tags or equivalent

The equivalent of GL contexts or render contexts.

Something something CLIM.

Perhaps menus/ribbons/widgetbars/action bars on the top of the screen and (vim/emacs like) status line and command bar on the bottom of the screen for the focussed application. Glyphs on the title bar of windows for common status effects (eg unsaved changes, offline/online/autistic mode/background data/insecure connection, attention wanted, new message received, audio playing, wants to go fullscreen, permission request, authentication request, logged in/out, etc etc etc). Vim for everything. Focus, attention, and backgrounded/suspended status through shades + glow + blur + frosted glass + water + smoke + etc etc.

Stained glass style translucency?

Systray, notifications, and android like quick widgets/notification cards.

Translucency, brightness/saturation, and z-order all different aspects of focus.

System overlay for system menus, system command bar etc. This lets you edit system buffers to do eg window management.
