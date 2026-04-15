# Automated-Warehouse-Robot-Planning-Answer-Set-Programming-ASP-
Automated Warehouse Robot Planning : Answer Set Programming (ASP)

Designed and implemented a logic-based multi-robot planning system for an automated warehouse environment using Answer Set Programming (ASP) with Clingo inspired by the ASP Challenge 2019.

• Modeled a dynamic warehouse as a discrete time-step system: encoded robots, shelves, picking stations, products, and orders as ASP predicates, with inertia rules to propagate state across time steps and handle the frame problem.
• Engineered hard constraints for collision avoidance (no two robots/shelves on same node), anti-swap prevention (blocking position exchanges across consecutive steps), highway restrictions, and grid boundary enforcement across a 16×16 warehouse grid.
• Implemented full action semantics : robot movement (4-directional), shelf pickup/putdown, and order delivery with carrying-state fluents (free/carrying) and weighted cosine delivery verification logic.
• Validated across 5 warehouse instances, fulfilling 33 of 34 total orders with plan lengths ranging from 12 to 30 steps; applied #minimize optimization to reduce total robot action counts.

Tech: Answer Set Programming · Clingo · Declarative Logic Programming · Constraint Satisfaction · Temporal Reasoning · AI Planning
