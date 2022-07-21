# Type Hint for socket

## Solution

```python
import socket

sock: socket.SocketType = socket.socket(...)
socket_type: socket.SocketKind = socket.SOCK_STREAM  # or socket.SOCK_DGRAM
```

## References

More details to see [Type Hint on Python Handbook](https://leven-cn.github.io/python-handbook/recipes/core/type_hint).
