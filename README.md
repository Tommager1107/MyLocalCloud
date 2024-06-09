# MyLocalCloud

MyLocalCloud is a Windows application developed in C# using WPF and .NET Framework. It allows users to manage their game library, track playtime, and earn rewards based on their gaming habits. The application consists of a main UI for managing games and a background service that continuously tracks playtime.

## Features

- **Game Library Management:**
  - Add and remove games
  - View game details such as title, genre, and release date
- **Playtime Tracking:**
  - Automatically track playtime for each game
  - Manually enter playtime if needed
- **Achievements and Rewards:**
  - Set custom playtime goals
  - Earn rewards and badges for reaching milestones
- **Statistics and Analytics:**
  - View detailed playtime statistics with graphs and charts
  - Compare playtime across different games
- **User Profiles:**
  - Manage user profiles
  - Share achievements and playtime with friends
- **Cloud Backup and Sync:**
  - Local data storage with optional cloud backup and sync
  - Sync data across multiple devices

## Installation

### Prerequisites

- Windows operating system
- .NET Framework 4.8 or later

### Setup

1. **Download the Installer:**

   - Go to the [Releases](https://github.com/yourusername/MyLocalCloud/releases) page of this repository.
   - Download the latest installer from the releases section.

2. **Run the Installer:**

   - Execute the downloaded installer and follow the on-screen instructions to install MyLocalCloud.

3. **Start the Background Service:**

   - Open a command prompt with administrative privileges.
   - Navigate to the installation directory of MyLocalCloudService.
   - Install the service using the InstallUtil tool:

     ```bash
     InstallUtil.exe MyLocalCloudService.exe
     ```

   - Start the service using the following command:

     ```bash
     net start MyLocalCloudService
     ```

4. **Run the WPF Application:**

   - Launch MyLocalCloud from the start menu or installation directory to open the main UI.

## Usage

1. **Add a Game:**

   - Open the application and click on the "Add Game" button.
   - Enter the game details and save.

2. **Track Playtime:**

   - The background service will automatically track playtime when a game process is detected.
   - View playtime statistics in the application.

3. **Set Achievements and Rewards:**

   - Go to the game details view and set custom playtime goals.
   - Earn rewards for reaching milestones.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the developers of the .NET Framework and WPF for providing the tools to build this application.
- Special thanks to the open-source community for various libraries and tools used in this project.

## Contact

For any questions or feedback, please open an issue on the GitHub repository or contact the maintainer:

- GitHub: [yourusername](https://github.com/yourusername)
- Email: yourname@example.com
