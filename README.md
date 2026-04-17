# AmSC OpenMetadata - Tiled Sync

Start a Tiled subscription that sends a POST to OpenMetadata when a new node is created in Tiled's sandbox.

```python
uv run test.py
```

Then, write to the sandbox like:

```python
c['tst/sandbox'].write_array([1,2,3], metadata={'color': 'blue', 'mood': 'elated', 'description': 'Time for some American Science, amiright?', 'uid': str(uuid.uuid4())})
```
