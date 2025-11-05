# 🛍️ Vastrado Mock API

A mock REST API for the Vastrado Clone Flutter App.

## 🚀 How to Deploy on Render

1. Go to [Render](https://render.com) and sign up using GitHub.
2. Create a **new Web Service** and connect this repository.
3. Set environment and commands:

   - Environment: **Node**
   - Build Command: `npm install`
   - Start Command: `npm start`

4. After deployment, your API will be live at:

   ```
   https://<your-app-name>.onrender.com/products
   ```

Use this endpoint in your Flutter app:

```dart
class ApiConstants {
  static const String base = 'https://<your-app-name>.onrender.com';
  static const String products = '$base/products';
}
```

Enjoy 🎉
