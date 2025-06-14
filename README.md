# Junior Developer Task – API (Vercel)

This is a Node.js (Express-based) serverless API for the Junior Developer task. It accepts a POST request containing a string, sorts its characters alphabetically, and returns the result as a JSON array.

## 🔧 Tech Stack

- Node.js
- Express
- Vercel (Serverless Deployment)

## Test

To hit the API endpoint, you'll use a POST request with JSON that looks like this:
{
  "data": "text"
}

## 📸 Screenshots
![Screenshot (282)](https://github.com/user-attachments/assets/e189dfee-d9bc-4d2a-9e3d-51054d0f6542)

## Using Postman

1. Open Postman.
2. Method: POST
3. URL: https://backend-junior-dev.vercel.app/
4. Go to Body tab → choose raw and JSON type.
5. Paste:
{
  "data": "example"
}
6. Send the request.
