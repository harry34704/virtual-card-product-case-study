# Lifecycle Logic

1. **Created**  
2. **Active**  
3. **Paused**  
4. **Canceled**

Transitions:
- Created → Active
- Active → Paused
- Paused → Active
- Active → Canceled
- Paused → Canceled

Each transition must:
- validate state
- emit event logs
- handle errors cleanly
