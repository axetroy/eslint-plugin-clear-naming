### Rules

| Rule | Description | Bad ❌                                   | Good ✅                                  |
| ---- | ----------- | ---------------------------------------- | ---------------------------------------- |
|      |             | `const url = new URL('xxx')`             | `const downloadURL = new URL('xxx')`     |
|      |             | `const ref = useRef(null)`               | `const containerRef = useRef(null)`      |
|      |             | `const [data, setData] = useState()`     | `const [user, setUser] = useState(null)` |
|      |             | `[].map(v => v)`                         | `[].map(element => element)`             |
|      |             | `const resp = await fetch()`             | `const response = await fetch()`         |
|      |             | `function app () { return <div></div> }` | `function App () { return <div></div> }` |
