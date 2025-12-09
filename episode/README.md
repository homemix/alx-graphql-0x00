# 📺 Episode Query — Fetch a Specific Episode by ID

This task focuses on learning how to request **specific data from a GraphQL API using arguments**. Using the Rick and Morty GraphQL API, you will write a query that fetches full details of a single episode by passing its **ID**.

---

## 🎯 Objective

Learners will write a **GraphQL query** to fetch details of a **specific episode** using its `id`.

---

## 📝 Task Instructions

🔹 Write a GraphQL query using the `episode(id: ID!)` field.

🔹 Your query **must include** the following fields:

| Field | Description |
|-------|-------------|
| `id` | Episode unique identifier |
| `name` | Episode title |
| `air_date` | When the episode aired |
| `episode` | The episode code (e.g., `S01E05`) |

---

## 🧪 Example Query

```graphql
query GetEpisodeById {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
