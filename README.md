# PIL-Rankings

Originally written to gather intel on competing teams during Premier Ice League, this is being released as a Trackmania API "quickstart" for others.

The Jupyter notebook should be self-explanatory, but it contains:
- API authentication
- CSV reading/writing
- SQLAlchemy with SQLite (and a pretty hetfy query)

**Not included**: username -> `account_id` resolution technique. Teams are listed in Discord by player names only, so I used fuzzy matching with `fuzzywuzzy` to find the best player (with the [trackmania.io](trackmania.io) API) and cleaned the remaining 5-10 incorrect matches manually.

---

Get in touch if you have questions:
- Trackmania: KCJ.TM
- Discord: kcjwv#7729
- LinkedIn: [https://linkedin.com/in/caseyjohnsonwv](https://linkedin.com/in/caseyjohnsonwv)
