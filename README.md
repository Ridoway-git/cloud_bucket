☁️ Cloudflare R2 Storage Uploader

![Cloudflare R2 GIF](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNzRscGtyaHBkNnpvcXJlbHkxMjQ4cXRvZGk5ZnN0bDMyMjF4eDE5diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/OGrrDjmqrCKec3zlix/giphy.gif)

A simple script/project to upload files directly to [Cloudflare R2](https://developers.cloudflare.com/r2/) – your affordable, S3-compatible object storage. This tool allows easy and efficient file uploads using your R2 bucket credentials.

---

🚀 Features

- ✅ Upload files to Cloudflare R2
- 📦 Supports large files
- 📁 Customize bucket name and path
- 🧪 Minimal and easy to use

🛠️ Setup & Usage

1. **Clone the repository:**

```bash
git clone https://github.com/Ridoway-git/cloud_bucket.git
cd cloud_bucket

npm install
node server.js

```
📁 Example Output
Upon successful upload, the script returns the file URL (based on your public bucket policy).

🧩 Notes
Make sure your R2 bucket is public if you want direct access to uploaded files.

You can extend the script to support batch uploads or directory syncing.

🙌 Credits
Developed by Ridoway
Powered by Cloudflare R2

📜 License
This project is licensed under the MIT License.
