1. Problem Statement
Market women in Makola and Oshodi lose 2–3 hours daily in queues because they lack timely information about vendor restock schedules, leading to wasted time and missed income opportunities.

2. Onion Decomposition
Layer	Description
Layer 1: Surface Symptom	Women wait 2–3 hours in queues.
Layer 2: Immediate Cause	Vendors run out of essentials quickly, forcing long waits until restock.
Layer 3: System Failure	No coordination or communication between suppliers, vendors, and buyers.
Layer 4: Root Constraint	Absence of a shared, low-cost scheduling or signaling system for restock times.

3. Algorithm (Pathway B — Physical Signal)

START
  WHEN supplier truck arrives at market gate
  THEN vendor hangs BLUE cloth on stall pole
  THEN women see cloth → continue shopping nearby
  WHEN vendor begins unloading tomatoes
  THEN vendor changes cloth to RED
  THEN women form orderly queue
  WHEN first 15 customers served
  THEN vendor removes cloth
END

 Reflection Questions
What surprised you when decomposing the queue problem?  
That the root issue wasn’t “too many buyers” but the lack of communication about restock timing.

Which detail was hardest to ignore during abstraction? Why?  
The emotional stress of mothers waiting in the sun—hard to ignore because it’s human-centered, but not essential data for solving the scheduling problem.

How would your algorithm fail if it rained heavily? (Edge case)  
Cloth signals might be invisible or damaged; women may not notice the color change. A backup (like a whistle or bell) would be needed.

One thing you’ll observe differently next time you’re in a queue:  
I’ll look for hidden patterns—like timing of supply arrivals—rather than just focusing on the length of the line.
