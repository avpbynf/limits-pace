# Changelog

## Unreleased

- Target percentage for the current moment of the week, with a progress bar and the time left
  before the reset.
- Targets at the start and end of today's working hours, and for every day of the week.
- Configurable reset weekday and time, and working hours.
- Works offline and installs as an app.
- The target ticks live as a rolling counter, with a configurable number of decimals, and the
  page reloads itself when a new version is published.
- Neumorphic interface following the system light or dark theme, in three layouts to choose
  from in the settings: Relief (one pill per working day), Cadran (a dial) and Barres (one
  column per day). Every setting is kept in the browser.
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
- The settings open in a sheet from the gear at the top right, and a button at the top left
  switches between light and dark. A change of layout sinks the view into the background and
  the new one rises out of it.
- The counter keeps its digits at four decimals: a digit that changes often rolls faster, the
  reel is recentred without a visible jump, and the columns are put back in place when the
  page comes back to the foreground.
