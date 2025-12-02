# DSA-30-days-challenge-
This repository documents my 30-day journey of mastering Data Structures &amp; Algorithms with the goal of improving problem-solving, coding efficiency, and logical thinking.

🔥 Challenge Goals

Strengthen core DSA fundamentals

Improve competitive programming & interview-oriented problem-solving

Develop consistency with daily coding habits

Prepare for FAANG / product-based company interviews

############################################################

2. Add Two Numbers
 LOGIC:

1)We create a dummy node so that we can easily build the result list.

2)We take a pointer l3 (starting from dummy) to attach new nodes for the answer.

3)We also use a carry variable to store extra value when the sum of digits is ≥ 10.

➤ Adding values

While both lists still have nodes:

Add l1 digit + l2 digit + carry.

The unit digit of the sum goes into the new node.

The carry becomes sum / 10.

Move to next nodes of both lists.

➤ If one list finishes earlier

If only l1 has remaining nodes:

Add each remaining digit + carry one by one.

If only l2 has remaining nodes:

Same process for l2.

➤ After both lists end

If carry is still not zero, add one last node for carry.

➤ Final return

Return dummy->next because the dummy node was only starting support.
