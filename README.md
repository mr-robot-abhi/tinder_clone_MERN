```
<h1 align="center">Tinder Clone ✨</h1>



## About This Project

- 🔐 **Authentication System** using JWT  
- 🛡️ **Route Protection** for secure access  
- 👤 **User Profile Management**: Create and update profiles  
- 🖼️ **Image Uploads** for profile customization  
- 🔄 **Swipe Feature**: Right/Left functionality  
- 💬 **Real-time Chat** for seamless messaging  
- 🔔 **Live Notifications** for updates  
- 🤝 **Matching Algorithm** for finding connections  
- 📱 **Responsive Design** for mobile-friendly UI  
- ⌛ ...and much more!  

---

## Configure Environment Variables

Create a `.env` file with the following details:

```bash
PORT=5000
MONGO_URI=<your_mongo_uri>
JWT_SECRET=<your_very_strong_secret>
NODE_ENV=development
CLIENT_URL=http://localhost:5173

CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
```
![Demo Screenshot](/client/public/tinder1.png)![Demo Screenshot](/client/public/tinder1.png)
---

## Run the App Locally

1. **Set Production Environment**  
   Update `NODE_ENV=production` and build the application:

   ```bash
   npm run build
   ```

2. **Start the Application**  
   Launch the app using:

   ```bash
   npm run start
   ```
```
