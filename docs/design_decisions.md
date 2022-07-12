# Design Decisions:

## First Thoughts:

* JSON file for initial load of data.
* Where to store changed data? If saved to JSON file and deployed to GitHub, will need commits to update JSON file - unlikely can do this through JS so prob not possible.
* onClick event to mark as done updates the timestamp (and resorts the containing list).
* Each containing list sorted by timestamp in desc order.
* Not planning to have authentication and authorization at least not yet - just for personal use and for consolidating learning TypeScript and React and testing frameworks at this point.
