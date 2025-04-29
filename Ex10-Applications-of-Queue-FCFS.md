# Ex10 Applications of Queue – FCFS
## DATE:
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1.  Start with process, burst time, and waiting time arrays.
2.	Loopthrough each process from i= 0 to n-1.
3.	Compute tat[i] = burst_time[i] + wait_time[i].
4.	End the algorithm.

  
## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: Preethi J 
RegisterNumber:  212223220080
*/
```

```
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
// calculating turnaround time byadding
// burst_time[i] + wait_time[i] int i;
for ( i = 0; i < n ; i++)
tat[i] = burst_time[i] + wait_time[i]; return 0;
}


```

## Output:
![image](https://github.com/user-attachments/assets/95f13117-5da7-4a30-aed4-372d973eeaa8)




## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
