## GraphiQL

```javascript
{
  songs {
    id
    title
    lyrics {
      content
    }
  }
}
```

```javascript
mutation {
  addSong(title: "Cold Night") {
    id
  }
}
```

```javascript
mutation {
  addLyricToSong(songId: "603ed22d2564095fcc00b115", content: "Oh my it's a cold night") {
    id
  }
}
```

