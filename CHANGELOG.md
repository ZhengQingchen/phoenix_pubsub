# Changelog

## v1.0.2 (2017-06-14)

* Bug fixes
  * Fix presence "zombies" / "ghosts" caused by replicas receiving downed pids for remote replicas they never observe

## v1.0.1 (2016-09-29)

* Enhancements
  * Support passing a function to `Tracker.update` for partial metadata updates
  * Prevent duplicate track registrations when calling `Tracker.track`

* Bug fixes
  * [PG2] - Fix multinode broadcasts requiring the same pool_size to properly broker messages

## v1.0.0 (2016-06-23)

* Enhancements
  * Extract `Phoenix.PubSub` into self-contained application
  * Add `Phoenix.Tracker` for distributed presence tracking for processes
