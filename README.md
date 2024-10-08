# noorAlmobin

Welcome to **noorAlmobin**, a PWA Book & Calendar Application! This project integrates a calendar, the Quran, Nahj al-Balagha, and several other books into a single, user-friendly Progressive Web App (PWA). Developed using **Deno Fresh** for the frontend and **Deno Lesan** for the backend, this application aims to provide an accessible platform for engaging with important texts and managing schedules seamlessly.

This project just used for testing some github action and other technologies, maybe in later this project find own way.

## Features

- **Interactive Calendar**: Manage your events, reminders, and important dates effortlessly.
- **Quran**: Access the full text of the Quran, including translations and audio recitations.
- **Nahj al-Balagha**: Explore the wisdom of Nahj al-Balagha with searchable text and commentary.
- **Nahj al-Fasahe**: Explore the wisdom of Nahj al-Fasahe with searchable text and commentary.
- **Additional Books**: Read and navigate through a selection of other significant texts.
- **Offline Access**: Enjoy the app's features even without an internet connection, thanks to PWA capabilities.
- **Responsive Design**: Designed to work on various devices, providing a seamless experience on mobile and desktop.

## Technology Stack

- **Frontend**: [Deno Fresh](https://fresh.deno.dev/) for a modern, reactive user interface.
- **Backend**: [Deno Lesan](https://deno.land/x/lesan) for RESTful API handling.
- **Database**: [MongoDB](https://www.mongodb.com/) for efficient data storage and retrieval.
- **Service Workers**: To enable offline functionality and enhance performance.

## Installation

To install and run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/noorAlmobin.git
   ```

2. Navigate to the project directory:
   ```bash
   cd noorAlmobin
   ```

3. Install Deno (if you haven't already):
   Follow the instructions at [deno.land](https://deno.land/#installation).

4. Start the backend server with Deno Lesan:
   ```bash
   deno run --allow-net --allow-read --allow-write src/backend/server.ts
   ```

5. Start the frontend with Deno Fresh:
   ```bash
   deno task start
   ```

6. Open your browser and go to `http://localhost:8000`.

## Usage

Once the application is running, you can:

- Navigate through the calendar to add and manage events.
- Access the Quran and Nahj al-Balagha through dedicated sections.
- Use the search functionality to find specific verses or passages.
- Save your reading progress and bookmarks for easy access later.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to submit a pull request or open an issue.

### How to Contribute

1. Fork the repository.
2. Create your feature branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to all contributors and the open-source community for their invaluable resources and support.
- Inspiration from various educational and religious texts.

## Contact

For any inquiries or feedback, feel free to reach out:

- Email: hemedani@gmail.com
- GitHub: [hemedani](https://github.com/hemedani)

---
