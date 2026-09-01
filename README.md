# Image Resizer Tool

A powerful web-based image resizer that offers two distinct resizing options: pixel dimensions and file size optimization. This tool provides an intuitive interface for batch processing images with real-time previews and carousel viewing.

## ✨ Features

### 🎯 Two Resizing Options

#### Option 1: Resize by Pixel Dimensions
- Set custom width and height values
- Maintain aspect ratio with optional height auto-calculation
- View results in an interactive carousel
- Download individual images or all at once

#### Option 2: Resize by File Size
- Target specific file sizes in KB
- Smart algorithm handles both increasing and decreasing file sizes
- Automatically adjusts quality and dimensions to achieve target size
- Results grid with before/after size comparison
- Batch download functionality

### 🖼️ Image Management
- **Drag & Drop** support for multiple images
- Click to browse and select images
- Thumbnail preview with dimensions
- Remove individual images from the queue
- Support for JPG, PNG, and WEBP formats

### 🎨 User Interface
- Clean, modern design with gradient backgrounds
- Responsive layout for all screen sizes
- Interactive mode switching
- Progress bar for file size resizing operations
- Keyboard navigation (arrow keys) in carousel view

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- No server required - runs entirely in the browser

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/image-resizer-tool.git
   ```

2. **Open the application**
   ```bash
   cd image-resizer-tool
   open index.html
   ```
   Or simply double-click the `index.html` file in your browser.

### Usage

1. **Upload Images**
   - Click the upload area or drag and drop images
   - Supported formats: JPG, PNG, WEBP

2. **Choose Resizing Mode**
   - Click "Option 1" for dimension-based resizing
   - Click "Option 2" for file size-based resizing

3. **Option 1: Dimension Resizing**
   - Enter target width (required)
   - Enter target height (optional - auto-calculated to maintain aspect ratio)
   - Click "Apply & View Carousel"
   - Use navigation buttons or arrow keys to browse images
   - Download individual images or all resized images

4. **Option 2: File Size Resizing**
   - Enter target file size in KB
   - Click "Apply Changes"
   - View results with original vs new size comparison
   - Download individual images or all at once

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Structure and semantic markup
- **CSS3**: Modern styling with gradients, animations, and responsive design
- **Vanilla JavaScript**: No external dependencies
- **Canvas API**: Image processing and resizing
- **File API**: File handling and blob manipulation

### How It Works

#### Dimension Resizing
- Uses HTML Canvas to redraw images at specified dimensions
- Maintains aspect ratio when height is auto-calculated
- Outputs as JPEG with 92% quality for optimal size/quality balance

#### File Size Resizing
- Implements a binary search algorithm to find optimal quality/dimensions
- **For increasing size**: Scales up dimensions while maintaining quality
- **For decreasing size**: Reduces quality first, then dimensions if needed
- Handles both scenarios with precision targeting (within 3% tolerance)

## 🎯 Use Cases

- **Web Optimization**: Reduce image sizes for faster loading websites
- **Social Media**: Resize images to platform-specific dimensions
- **Email Attachments**: Compress images to fit attachment size limits
- **Print Preparation**: Adjust image dimensions for printing
- **Batch Processing**: Process multiple images simultaneously

## 🔒 Privacy & Security

- **100% Client-Side**: All processing happens in your browser
- **No Uploads**: Images never leave your device
- **No Tracking**: No analytics or external requests
- **No Storage**: Images are not stored or cached

## 🛠️ Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Opera 47+

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 📝 License

This project is open source and available under the MIT License.

## 📞 Support

For issues, questions, or contributions:
- Open an issue in the GitHub repository
- Submit a pull request for bug fixes or features

## 🙏 Acknowledgments

- Icons and emojis used for visual enhancement
- Inspired by common image processing needs in web development
- Built with focus on user experience and performance

---

**Made with ❤️ for everyone who needs quick and easy image resizing**
