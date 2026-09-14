# FleetMend — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Garage planner

- As a garage planner, I want a ranked list of vehicles likely to need service this week, so I pull them before they fail on a customer site.
- As a garage planner, I want to see why a vehicle scored high (age, mileage, prior transmission work), so I trust the queue.

### Dispatcher

- As a dispatcher, I want risk scores in the assignment board, so I avoid sending a high-risk vehicle on a long remote job.

### Parts planner

- As a parts planner, I want aggregate predicted repair classes, so I stage parts before the rush.

### Fleet operations manager

- As a fleet ops manager, I want unplanned downtime and garage-visit KPIs versus the old PM calendar, so I can defend the program to finance.
- As a fleet ops manager, I want per-garage model health, so one bad site does not poison the fleet.

### Data analyst

- As a telematics analyst, I want imbalance and drift reports, so I know when to retrain on a fresh window.
- As a telematics analyst, I want exclusion rates for invalid rows, so I can fix upstream data feeds.

### Compliance / SLA manager

- As an SLA manager, I want auditable links from scores to completed work, so customer uptime reports are defensible.
- As a compliance officer, I want driver-behavior features off by default, so we do not create an HR surveillance product by accident.
