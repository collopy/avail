avail prints a list of times when the user is available for meetings based on events from their Mac calendar. It relies on the command line tools icalBuddy, which Homebrew users can install with "brew install ical-buddy," and gdate, installed with “brew install coreutils.”

# Options
-c: By default, avail uses an Apple calendar titled “Calendar.” This flag modifies that. Example: "-c Work"
-d: By default, avail lists availability for the next 14 days. This flag modifies that. Example: "-d 30"
-m: By default, avail only lists available times at least 60 minutes long. This flag modifies that. Example: "-m 30"
-s: By default, avail starts available time during the day at 9:00. This flag modifies that. Example: "-s 8:00"
-s: By default, avail ends available time during the day at 17:00. This flag modifies that. Example: "-s 18:00"
-l: By default, avail reserves time for a lunch break. This flag prevents that.
-S: By default, avail starts the lunch break at 12:00. This flag modifies that. Example: "-S 12:30"
-E: By default, avail ends the lunch break at 1:00. This flag modifies that. Example: "-S 14:00"
-w: By default, avail doesn’t list availability on weekends. This flag makes weekends available.
-r: By default, avail lists times when the user is working remotely as available. This flag makes it only list times when the user is working on site.
-R: By default, avail regards any day with an all-day event titled “Remote work” as time working remotely. This flag modifies that. Example: "-R 'WFH'"
-p: This one's complicated.
