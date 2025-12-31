```sql
> SELECT name, role, background, mission FROM developers 
  WHERE username = 'infinawaz';
```

| name | role | background | mission |
| :--- | :--- | :--- | :--- |
| **Md Shahnawaz** | Software Engineer | `Mathematics` `CS` | Building logic into beauty through optimization. |

<br>

```sql
> SELECT language, frameworks, infrastructure FROM skills;
```

| language | frameworks | infrastructure |
| :--- | :--- | :--- |
| `Python` | `FastAPI` | `Docker` |
| `TypeScript` | `React` | `Git` |
| `JavaScript` | `Node.js` | `Linux` |
| `SQL` | `Express` | `SQLite` |

<br>

```sql
> SELECT name, stack, description FROM projects 
  WHERE status = 'Deployed' 
  ORDER BY impact DESC;
```

| name | stack | description |
| :--- | :--- | :--- |
| **[socketio-multiroom-chat](https://github.com/infinawaz/socketio-multiroom-chat)** | `Node.js` `Socket.io` | Real-time messaging architecture with dynamic room allocation. |
| **[AsyncMeteo](https://github.com/infinawaz/AsyncMeteo)** | `FastAPI` `Python` | Asynchronous high-throughput weather forecasting API. |
| **[Ultimate Sorting Visualizer](https://github.com/infinawaz/ultimate-sorting-visualizer)** | `React` `TS` | Frontend visualization engine for complex sorting algorithms. |
| **[Salon City](https://github.com/infinawaz/hair_salon)** | `Full Stack` `MVC` | Enterprise-grade management system for beauty service providers. |
| **[Errfriendly](https://github.com/infinawaz/errfriendly)** | `Python` `PyPI` | Human-readable exception handling interface for developers. |

<br>

```sql
> SELECT * FROM contact_channels;
```

| channel | address | status |
| :--- | :--- | :--- |
| **Email** | [shahanwazdgp07@gmail.com](mailto:shahanwazdgp07@gmail.com) | `CONNECT_OPEN` |
| **LinkedIn** | [linkedin.com/in/md-shahnawaz-alam-khan](https://linkedin.com/in/md-shahnawaz-alam-khan-7b2121179/) | `CONNECT_OPEN` |
| **GitHub** | [github.com/infinawaz](https://github.com/infinawaz) | `ACTIVE_SOURCE` |

<br>

`4 rows in set (0.01 sec)`
