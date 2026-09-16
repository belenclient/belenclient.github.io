# Banner Cache

This folder stores the profile/home banners that Belen users set.

When you set a banner in the Belen theme, the extension writes your banner to a
small JSON file here named `banner_cache/{userId}.json` instead of (or in
addition to) the local browser storage. That way, the banner you choose follows
you across devices and is visible to any other Belen user who opens your profile.

When you change your banner, the extension overwrites this file (and removes the
old uploaded banner image if one existed), so only your current banner is
stored.

This folder is managed automatically by the extension. You do not need to edit
anything here by hand.

Files are written only by users with a GitHub token configured in the Belen
extension options.