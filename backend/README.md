


```bash
npm install
```


```bash
cp .env.example .env
```

Variables used: `DATABASE_URL` (e.g. `file:./dev.db` for SQLite) and `JWT_SECRET`.



```bash
npm run migrate
```


```bash
npm run seed
```


```bash
npm run dev
```

The server runs on port **4000** (or the value set in `PORT` in `.env`).
For operations that require login, use the **HTTP Headers** section and pass the token:

```json
{
  "Authorization": "Bearer YOUR_JWT_TOKEN"
}
```