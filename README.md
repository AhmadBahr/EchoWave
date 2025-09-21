# 🎵 EchoWave

[![Django](https://img.shields.io/badge/Django-2.2.4-092E20?style=for-the-badge&logo=django&logoColor=white)](https://djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)](https://github.com/yourusername/EchoWave)
[![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)](https://github.com/yourusername/EchoWave/releases)

A modern web-based music player built with Django, featuring synchronized lyrics, audio playback controls, and a clean user interface.

## ✨ Features

- 🎶 **Music Playback**: Play audio files with full media controls
- 📝 **Synchronized Lyrics**: Real-time lyrics display synchronized with audio
- 🎨 **Modern UI**: Clean and responsive design with Bootstrap integration
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- 🗂️ **Song Management**: Upload and manage your music library
- ⏯️ **Media Controls**: Play, pause, skip, and seek functionality
- 🖼️ **Album Art**: Display album covers and artist information

## 🚀 Quick Start

### Prerequisites

- Python 3.6 or higher
- Django 2.2.4
- pip (Python package installer)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/EchoWave.git
   cd EchoWave
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install django
   ```

4. **Run migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a superuser (optional)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Start the development server**
   ```bash
   python manage.py runserver
   ```

7. **Open your browser**
   Navigate to `http://127.0.0.1:8000/` to view the application.

## 📁 Project Structure

```
EchoWave/
├── App/                    # Main Django application
│   ├── models.py          # Database models
│   ├── views.py           # View functions
│   ├── urls.py            # URL patterns
│   ├── templates/         # HTML templates
│   │   ├── index.html     # Main page
│   │   └── main.html      # Music player component
│   └── static/            # Static files (CSS, JS)
├── MusicPlayer/           # Django project settings
│   ├── settings.py        # Project configuration
│   └── urls.py            # Main URL configuration
├── media/                 # User uploaded files
├── db.sqlite3            # SQLite database
└── manage.py             # Django management script
```

## 🎵 Usage

1. **Adding Songs**: Use the Django admin interface to add songs with metadata
2. **Playing Music**: Click on any song to start playback
3. **Lyrics**: Lyrics will automatically sync with the audio playback
4. **Controls**: Use the media player controls to manage playback

## 🛠️ Technologies Used

- **Backend**: Django 2.2.4
- **Database**: SQLite
- **Frontend**: HTML5, CSS3, JavaScript
- **Media Player**: MediaElement.js
- **Styling**: Bootstrap, Font Awesome

## 📝 API Endpoints

- `/` - Main music player interface
- `/admin/` - Django admin interface for song management

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Django community for the excellent framework
- MediaElement.js for the media player functionality
- Bootstrap for the responsive design components

---

[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)](https://github.com/yourusername/EchoWave)
[![Star this repo](https://img.shields.io/github/stars/yourusername/EchoWave?style=for-the-badge)](https://github.com/yourusername/EchoWave/stargazers)
[![Fork this repo](https://img.shields.io/github/forks/yourusername/EchoWave?style=for-the-badge)](https://github.com/yourusername/EchoWave/network/members)
