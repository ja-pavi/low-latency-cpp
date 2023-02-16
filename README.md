# Low latency trading infrastructure in CPP, WIP

Performances 

Execute an order with brand new Limit price:  O(log(n)) 
Execute an order whose limit price currently exists in the order book:  O(1)
Update an order:  O(1)
Cancel an order:  O(1)
Perform order book analysis:   O(log(n))
