# Shahnawaz API Reference

**Base URL**: `https://github.com/infinawaz`  
**Version**: `v3.1.0`  
**Status**: ![System Status](https://img.shields.io/badge/System_Status-Operational-success?style=flat-square)

---

## `GET /about`

Returns current developer profile and mathematical background info.

**Response** `200 OK`

```json
{
  "name": "Md Shahnawaz",
  "title": "Software Engineer",
  "background": ["Mathematics", "Computer Science"],
  "mission": "Building logical beauty through code optimization.",
  "status": "Solving variable equations"
}
```

---

## `GET /skills`

Returns a list of technical capabilities and active stacks.

**Response** `200 OK`

```json
{
  "languages": ["Python", "JavaScript", "TypeScript", "SQL"],
  "frameworks": ["React", "Node.js", "FastAPI", "Express"],
  "infrastructure": ["Docker", "Git", "Linux", "SQLite"],
  "concepts": ["Abstract Algebra", "System Design", "Algorithms"]
}
```

---

## `GET /projects`

Retrieves the list of deployed services and open source contributions.

**Response** `200 OK`

| Resource | Method | Description | Stack |
| :--- | :--- | :--- | :--- |
| **[socketio-multiroom-chat](https://github.com/infinawaz/socketio-multiroom-chat)** | `GET` | Real-time chat architecture. | `Node.js` `Socket.io` |
| **[AsyncMeteo](https://github.com/infinawaz/AsyncMeteo)** | `GET` | Asynchronous weather API. | `FastAPI` `Python` |
| **[Ultimate Sorting Visualizer](https://github.com/infinawaz/ultimate-sorting-visualizer)** | `GET` | Frontend algorithm engine. | `React` `TS` |
| **[Salon City](https://github.com/infinawaz/hair_salon)** | `GET` | Salon management system. | `Full Stack` `MVC` |
| **[Errfriendly](https://github.com/infinawaz/errfriendly)** | `GET` | Human-readable exception interface. | `Python` `PyPI` |

---

## `POST /contact`

Initiates a communication channel.

**Parameters**

| Name | Type | Description |
| :--- | :--- | :--- |
| **email** | `string` | [shahanwazdgp07@gmail.com](mailto:shahanwazdgp07@gmail.com) |
| **linkedin** | `url` | [Connect Profile](https://linkedin.com/in/md-shahnawaz-alam-khan-7b2121179/) |
| **github** | `url` | [Source Code](https://github.com/infinawaz) |

**Response** `201 Created`

```json
{
  "message": "Connection established successfully."
}
```
