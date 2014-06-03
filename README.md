---
title: Looks innocuous...
except
- it's not

development: &default
  adapter: postgresql
  database: dev_development
  
production:
  <<: *default
  database: test_production
---

_Raw_ content should be represented.
