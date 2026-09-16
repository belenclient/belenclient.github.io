# Banner Cache

This folder stores the profile/home banners that Belen users set.

When a user sets a banner in the Belen theme, the extension writes
`banner_cache/{userId}.json` here directly through the GitHub Contents API.
The Belen theme reads the banners from this folder.

That way, the banner you choose follows you across devices and is visible to
any other Belen user who opens your profile.

When you change your banner, the file is overwritten with the new banner
(and if a user's entry is removed, the file is deleted), so only current
banners are stored here.

This folder is managed automatically. You do not need to edit anything here
by hand.