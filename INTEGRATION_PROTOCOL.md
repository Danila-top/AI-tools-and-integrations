# Integration protocol

1. Identify the exact resource.
2. Read current state before mutation.
3. Perform the smallest useful write.
4. Verify the resulting state.
5. Record the operation and relevant identifier.

For destructive operations, require a stronger verification step than for ordinary documentation changes.
