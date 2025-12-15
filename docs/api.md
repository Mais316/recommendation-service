# API Documentation

## Endpoints

### GET /recommendations

Get personalized recommendations.

**Parameters:**
- `userId` (string, required): The user ID

**Response:**
```json
{
  "recommendations": [
    {
      "id": "1",
      "title": "Recommended Item",
      "score": 0.95
    }
  ]
}
```

**Example:**
```bash
curl http://localhost:3000/recommendations?userId=123
```

### GET /health

Health check endpoint.

**Response:**
```json
{
  "status": "ok"
}
```
