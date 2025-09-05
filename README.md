# Travel Itinerary Generator with Bolt and Supabase

This project helps you generate travel itineraries using [Bolt](https://bolt-js.netlify.app/) and [Supabase](https://supabase.com/). It provides a modern, collaborative way to plan trips, leveraging real-time data storage and retrieval.

## Features

- **Create and Manage Itineraries:** Build day-by-day plans for your trips.
- **Real-time Collaboration:** Collaborate with friends or family using Bolt's reactive UI.
- **Cloud Storage:** All itineraries are stored securely in Supabase.
- **Easy Setup:** Just clone, configure, and start planning!

## Getting Started

### Prerequisites

- Node.js and npm installed
- Supabase account (for backend)
- Bolt (for frontend)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ankitagrwal/travel_itinerary.git
    cd travel_itinerary
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Configure Supabase:**
    - Sign up at [Supabase](https://supabase.com/), create a new project.
    - Get your API keys and database URL.
    - Copy `.env.example` to `.env` and add your Supabase credentials.

4. **Start Development Server:**
    ```bash
    npm run dev
    ```

## Usage

- Open the app in your browser.
- Sign in or create a new itinerary.
- Fill in your travel details (destinations, dates, activities).
- Invite collaborators if needed.

## Technologies Used

- **Bolt:** For building fast, reactive web apps.
- **Supabase:** For database, authentication, and backend functions.

## Contributing

Feel free to open issues or submit pull requests for new features, bug fixes, or improvements!

## License

MIT