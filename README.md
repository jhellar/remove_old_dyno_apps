# Remove old dyno apps

Script which will help to remove old applications from dyno farm.

Configuration for fhc and dyno is in remove_old_apps.js file. Script will remove applications older than number of days specified in remove_old_apps.js file.

Script also outputs names of apps found in dyno, not found using fhc. Reason for such applications may be that they are in different domain or they have not been deleted successfully and may be deleted from dyno farm.
