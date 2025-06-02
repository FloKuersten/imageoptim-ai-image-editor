
Built by https://www.blackbox.ai

---

# ImageOptim

## Project Overview

ImageOptim is an advanced image optimization tool designed to enhance and transform images through AI-powered technology. It supports various features essential for social media users, providing professional-grade image editing capabilities. The platform allows users to remove backgrounds, apply 3D effects, and watermark images, ensuring high-quality outputs tailored to specific social media requirements.

## Installation

To run ImageOptim locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd imageoptim
   ```
2. **Open the `index.html` file** in your web browser. The application does not require a server to run and is fully client-side.

**Note**: Ensure you have an internet connection as the application uses external libraries from CDNs.

## Usage

1. **Home Page**: Start at the home page where you can access features, pricing, and the image editor.
2. **Image Editor**: Click on "Try Now" to navigate to the image editor where you can upload images for editing.
3. **Editing**: Use the upload functionality to import images. Then adjust brightness, contrast, and saturation, or apply advanced AI features like background removal and 3D effects.
4. **Saving**: After editing, download your optimized image directly.
5. **User Authentication**: Users can log in to access their dashboard and manage credits.

## Features

- **AI Background Removal**: Remove backgrounds instantly using AI.
- **3D Effects**: Add depth to images with advanced 3D effects.
- **Watermarking**: Add or remove watermarks easily.
- **Multiple Pricing Plans**: Choose from free, pro, or pay-per-use options.
- **Intuitive UI**: Designed with user experience in mind, including drag-and-drop features for image uploading.

## Dependencies

The project relies on several external libraries for its functionalities. The main dependencies include:

- [Tailwind CSS](https://tailwindcss.com)
- [FontAwesome](https://fontawesome.com)
- [GSAP](https://greensock.com/gsap/)
- [Three.js](https://threejs.org)
- [Stripe.js](https://stripe.com/docs/js)

You can find these libraries linked in the `<head>` section of the HTML files.

## Project Structure

The project follows a simple HTML structure with multiple important files:

```
├── index.html          # Main landing page
├── image-editor.html   # Image editing interface
├── admin.html          # Admin panel for user management
├── success.html        # Payment success page
├── canceled.html       # Payment cancellation page
└── [other HTML files]  # Additional functionality pages
```

### Key Files:

- **index.html**: The landing page that features the main navigation, hero section, and links to other parts of the application.
- **image-editor.html**: The core functionality for image upload and editing.
- **admin.html**: Admin interface for managing users and viewing statistics.
- **success.html**: Confirmation page displayed after a successful payment.
- **canceled.html**: Page shown if a payment is canceled.

---

Feel free to contribute to the project or raise any issues. Your feedback will help enhance ImageOptim.