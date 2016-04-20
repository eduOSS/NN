1. in high-level pseudo-code, batch back-propagation is:    
```   
 loop maxepochs times   
   for-each data item   
     compute a gradient for each weight and bias   
     accumulate gradient   
   end-for   
   use accumulated gradients to update each weight and bias   
 end-loop   
```
   
2. in high-level pseudo-code, stochastic back-propagation is:   
```
 loop maxepochs times   
   for-each data item   
     compute gradients for each weight and bias   
     use gradients to update each weight and bias   
   end-for   
 end-loop   
```   
3. in pseudo-code, mini-batch training is:     
```   
 loop maxepochs times   
   loop until all data items used   
     for-each batch of items   
       compute a gradient for each weight and bias   
       accumulate gradient   
     end-batch   
     use accumulated gradients to update each weight and bias   
   end-loop all item   
 end-loop   
```
