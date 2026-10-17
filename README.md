# AnimeTracker 🍜

A modern anime discovery and tracking web application built with React and powered by the AniList GraphQL API.

[**Live Demo**](https://a4anime.vercel.app/)

## Overview

AnimeTracker is a web application for discovering anime, managing a personal watchlist, tracking viewing progress, and exploring currently airing series.

Inspired by existing anime tracking platforms, the project reimagines the browsing and tracking experience through a modern interface, clear information hierarchy, and streamlined navigation. The goal is to make discovering new series and managing an anime watchlist feel intuitive across desktop and mobile devices.

## Features

- **Anime Discovery** — Explore popular, highly rated, seasonal, and genre-based anime.
- **Personal Watchlist** — Organize anime by watch status and keep track of viewing progress.
- **Anime Details** — Explore series information, episode counts, ratings, recommendations, and related content.
- **Seasonal Calendar** — Browse currently airing anime and see which days new episodes are scheduled.
- **User Profiles** — Manage profile information, favorites, and viewing statistics.
- **Authentication** — Create an account and access personalized anime lists and saved progress.
- **Persistent Data** — Save watchlists, viewing progress, ratings, and profile information across sessions.

## Tech Stack

| Technology | Purpose |
|---|---|
| React | Component-based user interface |
| Vite | Development server and build tooling |
| JavaScript | Application logic |
| CSS | Responsive styling and layout |
| AniList GraphQL API | Anime data and metadata |
| Supabase | Authentication and persistent user data |
| React Router | Client-side navigation |
| Lucide React | Interface icons |

## Design & Development

AnimeTracker combines front-end development with UX/UI design, focusing on:

- **Responsive Design** — Adapting browsing and tracking experiences to different screen sizes.
- **Information Hierarchy** — Organizing anime metadata, viewing progress, and navigation for easy scanning.
- **Reusable Components** — Building modular React components to support consistent layouts and interactions.
- **API Integration** — Fetching and organizing anime data from the AniList GraphQL API.
- **User Authentication** — Connecting account access to personalized features.
- **Data Persistence** — Saving user-specific information with Supabase.
- **Navigation & Routing** — Structuring the application into distinct browsing, tracking, calendar, and profile experiences.

## API & Data

Anime metadata is provided by the [AniList GraphQL API](https://anilist.gitbook.io/anilist-apiv2-docs/).

Supabase supports authentication and persistent user data, including watchlists, viewing progress, ratings, and profile information.

## Acknowledgments

- [AniList](https://anilist.co/) for providing anime data through its GraphQL API.
- [Supabase](https://supabase.com/) for authentication and data persistence.
