## Simple Voice Chat App

## Overview
A simple voice chat application built using .NET MAUI for the frontend and ASP.NET Core with SignalR for the backend. This project showcases real-time communication capabilities and serves as a great learning resource for working with modern web technologies.

## Features
- Real-time voice communication between users.
- User-friendly interface built with .NET MAUI.
- Scalable backend powered by ASP.NET Core and SignalR.
- Lightweight and easy to deploy.

## Technologies Used
- **Frontend**: [.NET MAUI](https://docs.microsoft.com/en-us/dotnet/maui/)
- **Backend**: [ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/)
- **Real-time Communication**: [SignalR](https://dotnet.microsoft.com/apps/aspnet/signalr)
- **Version Control**: [Git](https://git-scm.com/)
- **Hosting**: [GitHub](https://github.com)

## Installation

### Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download/dotnet) (version 6.0 or higher)
- [Visual Studio](https://visualstudio.microsoft.com/) with MAUI workload or any IDE supporting .NET development

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Reza-Tork/SimpleVoiceChat.git
   cd SimpleVoiceChat
   ```
2. **Navigate to the backend project for restore dependencies and build**:
   ```bash
   cd backend
   dotnet restore
   dotnet run
   ```
3. **Navigate to the frontend project for restore dependencies and build**:
   ```bash
   cd ../frontend
   dotnet restore
   dotnet run
   ```
### Usage
- Open your preferred browser and navigate to http://localhost:5000 (or the specified port for your backend) to start using the voice chat application.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.
Feel free to contribute!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.
