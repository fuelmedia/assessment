### Requirements:

- At start, you should fork this repo.
- Every step must be committed separately and commit messages **must**
  follow **semantic commit message** pattern.
- Project must being developed using
  - **Laravel Framework**, (with v9.32 if possible).
  - MySQL
  - Javascript Fetch API (for API calls)
- PHP Classes of project must follow SOLID design pattern.
- Variables, function names and class names must be chosen
  “understandable”.
- After finishing project you should make PR to this repository.

### Project Story:

One of our client wants to start-up **_Build Your Own PC_** business. They
gave us their product list (products.xlsx) which includes products model, make, price ($),
TDP’s (watt) and their compatibilities. They also want a flexible system so they can add new
products. Customers can only choose compatible parts (Ryzen 7th series CPU
can only be paired with A620, B650, X670 motherboards. PSU’s max wattage
should above the total TDP. Every motherboard have certain number of RAM
slot etc.). So we should store compatible parts somewhere of database. At
final, customers will select their parts and they will see final TDP and
price of system.

### Implementation Details

- There should be a **product** model and every product type should extend
  that class.
- You should use **Traits** for dependency injection between product
  types.
- Project must be implemented with Eloquent only (no DB::raw queries).
