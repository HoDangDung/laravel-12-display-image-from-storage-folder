# 🌟 laravel-12-display-image-from-storage-folder - Easy Image Upload and Display Tutorial

## 🚀 Getting Started

This guide helps you learn to upload and display images in Laravel 12 using the storage folder. You will discover how to use `Storage::url()` and serve files securely. Let’s begin!

## 📥 Download Now

[![Download](https://img.shields.io/badge/Download-v1.0-blue)](https://github.com/HoDangDung/laravel-12-display-image-from-storage-folder/releases)

## 🔍 What You Will Learn

In this tutorial, you will learn:

- How to upload images to your storage folder.
- How to set up `storage:link` for public access.
- How to securely serve files in your Laravel application.
- How to display images in Blade views.

## 📋 Requirements

Before you start, make sure you have these:

- PHP version 8.0 or higher.
- Composer installed on your machine.
- A web server such as Apache or Nginx.
- Basic knowledge of using a command line interface.

## 📦 Installation Steps

Follow these steps to download and set up the application:

1. **Visit the Releases Page:**
   Go to the [Releases page](https://github.com/HoDangDung/laravel-12-display-image-from-storage-folder/releases) in the repository.

2. **Download the Latest Version:**
   Find the latest version available and click the link to download the application files.

3. **Extract the Files:**
   Once downloaded, extract the files to a folder of your choice.

4. **Open Your Command Line:**
   Navigate to the extracted folder using the command line.

5. **Install Dependencies:**
   Run the following command to install the needed packages:
   ```
   composer install
   ```

6. **Set Up Environment Variables:**
   Copy the `.env.example` file and rename it to `.env`. Open the file and set your database details and other configurations.

7. **Generate Application Key:**
   Run this command to generate a unique application key:
   ```
   php artisan key:generate
   ```

8. **Set Up Storage Link:**
   Run this command to create a symbolic link from the public storage directory to the storage folder:
   ```
   php artisan storage:link
   ```

9. **Migrate Database:**
   Run the following command to set up the database tables:
   ```
   php artisan migrate
   ```

10. **Run the Application:**
    Start the Laravel development server with this command:
    ```
    php artisan serve
    ```
    Now visit `http://localhost:8000` in your web browser.

## 📷 Upload Images

To upload images:

1. Navigate to the upload section in the application.
2. Select an image file from your computer.
3. Click the upload button.

Once uploaded, you can easily view the images displayed in the app.

## 🌐 Display Images in Blade Views

To display images in your Blade views:

1. Use the `Storage::url($path)` helper function to generate the URL for your image.
2. Add an `<img>` tag in your Blade file.

Example:
```blade
<img src="{{ Storage::url('uploads/photo.jpg') }}" alt="Uploaded Image">
```

## ⚙️ Secure File Serving

Laravel provides ways to ensure that your files are secure. The `Storage` facade helps manage all your storage needs safely. Always check to make sure that only authorized users can access sensitive files. 

## 🛠 Troubleshooting

If you encounter issues:

- Check your web server configuration.
- Ensure your permissions are properly set for the storage folder. Use the command:
  ```
  chmod -R 775 storage/
  ```

- Verify your `.env` configuration.

## 🗂 Sample Project Structure

Here’s what your project structure should look like:
```
laravel-12-display-image-from-storage-folder/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
│   └── storage/  (linked to the storage folder)
├── resources/
│   └── views/
├── routes/
├── storage/
│   ├── app/
│   └── framework/
└── .env
```

## 🤝 Contributing

If you want to help improve this project, feel free to create a fork and submit a pull request. Your contributions are welcome!

## 📝 License

This project is open-source and available under the MIT License.

## 📅 Updates

Stay tuned for updates on new features, bug fixes, and improvements. Regular updates will enhance your user experience and keep the app running smoothly.

## ✅ Conclusion

You now have everything you need to download, set up, and utilize this Laravel 12 image upload and display tutorial. Follow the steps carefully, and you’ll have a functional application in no time.

For further assistance or questions, feel free to reach out! 

Remember to [Download](https://github.com/HoDangDung/laravel-12-display-image-from-storage-folder/releases) your copy today!