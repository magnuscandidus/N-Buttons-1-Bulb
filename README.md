# N-Buttons-1-Bulb
T = int(input())
for _ in range(T):
    N = int(input())  
    initial_states = input()  
    final_states = input()  
    num_toggles = sum(1 for i in range(N) if initial_states[i] != final_states[i])
    if num_toggles % 2 == 0:
        print("1") 
    else:
        print("0")  
