# Changelog

## Unreleased

- Target percentage for the current moment of the week, with a progress bar and the time left
  before the reset.
- Targets at the start and end of today's working hours, and for every day of the week.
- Configurable reset weekday and time, and working hours.
- Works offline and installs as an app.
- The target ticks live as a rolling counter, with a configurable number of decimals, and the
  page reloads itself when a new version is published.
- Neumorphic interface following the system light or dark theme, in two layouts to choose
  from in the settings: Relief (one pill per day) and Dial (an arc), each with the week listed
  under it. Every setting is kept in the browser.
- The week is drawn as the calendar week, Monday to Sunday, one gauge per day filling across
  its working hours. Hours outside the current session are shown dark.
- Working hours may end after midnight, and malformed settings fall back to their defaults.
- The settings use custom controls only: the reset day is a row of seven buttons and every
  time is picked on two scrolling wheels, so they work the same on a phone. The hours outside
  the session are shown in a soft grey instead of black. A tap on a visible row of a wheel picks
  it directly.
- The counter rolls every digit the same way, up when the target grows, without blur. The
  settings unfold and the page follows them down; a change of layout slides the view towards
  the chosen tab and any other change fades it in; the gauges ease to their new level.
- The page no longer scrolls when there is nothing below the fold.
- The interface is in English, set in Manrope, and the calendar week starts on Monday or
  Sunday as chosen in the settings.
- The settings open in a sheet from the gear at the foot of the screen, and the button beside
  it switches between light and dark, the whole page fading to the other theme. A change of
  layout sinks the view into the background and the new one rises out of it; any other change
  crossfades the view.
- The counter keeps its digits at four decimals: a digit that changes often rolls faster, the
  reel is recentred without a visible jump, and the columns are put back in place when the
  page comes back to the foreground.
- Days off can be ticked in the settings: no budget is spent on them and their gauge stays
  grey. The settings sheet closes by dragging its head down. The font is served with the page,
  so it is complete offline from the first visit.
- Both layouts fill the screen without scrolling: the week list takes the room left under the
  hero and the page scales down when even that is too tall. The frame is the same at the top
  and the bottom of the screen.
- The next reset is seven calendar days on, so a clock change no longer shifts it by an hour.
  The service worker keeps only good answers and always has an offline fallback, and a version
  missed while offline is picked up at the first fetch that succeeds. The sheet keeps the
  keyboard focus, Escape closes the picker before the sheet, the wheels commit where they
  snapped, and the counter reads as its value to a screen reader.
- A layout and a moment can be named in the address, to open the page on a given view or look
  at it at a given time; neither is kept.
