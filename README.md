# README

## Introduction

Currently following the Agile Web Development with Rails 8 course from Pragmatic Programmers.

Iteration A1 p73 completed.
Iteration A2.
- Added a seed item.
- Added css to product index to improve display
Iteration A3: Making the page update in real time.
- Added turbo stream p79
Playtime p81.
- Added hotwire-spark for changes refreshing in the browser automatically.

Adding debug/testing to repo.
- Added Ruby LSP, Ruby Debug, Ruby SolarGraph extensions to vscode.

Restarted Task B Validation and Unit Testing to see what I had missed.
Iteration B1 completed, however tests are failing as the tests don't build the data correctly
Iteration B2 completed, all tests passing now.
Iteration B2 Playtime. Added validation for product title to be at least 10 characters.


## History

v0.0 20260129 Inital build rubycritic score 96.73%, Code coverage 79.17%
v0.1 20260130 Finished iteration A, rubycritic score 96.73, code coverage 79.59%
v0.2 20260209 Finished Task B and playtime. Rubycritic score 95/19%, code coverage 80%


## Current issue

Up to p99 about to apply "One Final Change", but there are 11 tests failing at this point.
 Current state shows
 ```
ProductsControllerTest#test_should_get_new:
ActiveRecord::NotNullViolation: PG::NotNullViolation: ERROR:  null value in column "record_type" of relation "active_storage_attachments" violates not-null constraint
DETAIL:  Failing row contains (398878569, 95586318, 2026-02-01 20:00:41.820508, image, 398878569, null).

```
Checking code up to p96