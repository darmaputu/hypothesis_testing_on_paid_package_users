# hypothesis_testing_on_paid_package_users

DATA:

Table 'calls':
- `id`
- `user_id`
- `call_date`
- `duration`

Table 'internet':
- `id`
- `user_id`
- `session_date`
- `mb_used`

Table 'message':
- `id`
- `user_id`
- `message_date`

Table 'users':
- `user_id`
- `first_name`
- `last_name`
- `age`
- `city`
- `reg_date`
- `plan`
- `churn_date`

Table 'plan':
- `messages_included`
- `mb_per_month_included`
- `minutes_included`
- `usd_monthly_pay`
- `usd_per_gb`
- `usd_per_message`
- `usd_per_minute`
- `plan_name`

GOALS:
  1. The average income of users of Ultimate and Surf phone plans is different.
  2. The average income of users in the NY-NJ area is different from the income of users from other regions.

LIBRARY USED:
  - pandas
  - seaborn
  - matplotlib
  - numpy
  - scipy, stats
