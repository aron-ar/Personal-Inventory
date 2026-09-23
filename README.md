# Personal Item Inventory

A simple application to help users remember what they own, find where items are stored, and record decisions about them.

## Target User

People who own durable, infrequently used items and mainly rely on memory or informal lists to track them.

## MVP Scope

The MVP supports:

* Add, view, edit, delete, and search items.
* Two-level storage locations: `Level 1 → Level 2`.
* Item decisions: `Keep / Sell / Donate / Discard`.
* Configurable Categories, Storage Locations, and Units of Measure.
* `Active / Inactive` states for configurable values.

The system does not require users to create a complete inventory.

## Conventions & Limitations

* Users decide which items are worth registering.
* Search is based on item name.
* No search result does not mean the user does not own the item.
* Inactive configuration values are kept in the system and are not normally available for new items.
* The MVP does not include automatic duplicate detection, AI recommendations, marketplace integration, automatic selling/donation, or household collaboration.
* `How Often Used` and `Condition` use predefined values that cannot be modified by users.
