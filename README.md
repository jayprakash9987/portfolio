# Portfolio (No SMTP / No Nodemailer)

This project serves `index.html` with a small Express static server.

The contact form now sends directly through FormSubmit, so you do **not** need SMTP, Nodemailer, or `.env` email credentials.

## Run

```bash
npm install
npm start
```

Open: `http://localhost:3000/`

## Contact form behavior

- Frontend submits to `https://formsubmit.co/ajax/jayprakash95462@gmail.com`
- Messages are delivered to `jayprakash95462@gmail.com`
- Emails come in FormSubmit no-reply style
- First submission may require activation via FormSubmit confirmation email

## Notes

- `npm run dev` fails because no `dev` script exists
- Use `npm start`
