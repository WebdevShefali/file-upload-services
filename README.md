# File Upload Service Demos

A set of demos showing how to upload files using popular file upload services: **Filestack**, **Cloudinary**, **Uploadcare**, and **Transloadit**. Each demo includes file upload, preview, and performance tracking features.

These examples are perfect for learning, prototyping, or comparing services.

## Features

- Upload images, videos, and PDFs
- Preview uploaded files
- Apply basic transformations (resize, crop, rotate, etc.)
- Track upload and transformation performance (time, speed, total duration)

## Getting Started

### 1. Clone the repository

```bash
git clone <repo-url>
cd file-upload-services
```

### 2. Add your API keys

Each demo requires a service-specific API key:

- **Filestack**: Replace `YOUR_API_KEY` in `filestack.html`
- **Cloudinary**: Replace `YOUR_CLOUD_NAME` and `YOUR_PRESET` in `cloudinary.html`
- **Uploadcare**: Replace `YOUR_PUBLIC_KEY` in `uploadcare.html`
- **Transloadit**: Replace `YOUR_AUTH_KEY` in `transloadit.html`

### 3. Open in Browser

Simply open the HTML file you want to test in your browser.

## How It Works

1. Initialize the respective file upload service with your API key.
2. Open the file picker on button click.
3. Upload the file and track progress.
4. Preview the original and transformed files.
5. Display performance metrics such as upload time, speed, and transformation time.

## Resources

- [Filestack Documentation](https://www.filestack.com/docs/)
- [Cloudinary Documentation](https://cloudinary.com/documentation)
- [Uploadcare Docs](https://uploadcare.com/docs/)
- [Transloadit Docs](https://transloadit.com/docs/)
