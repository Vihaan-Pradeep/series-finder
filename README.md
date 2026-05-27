# Series Finder

A web application that helps users find every book in a series in the correct reading order. Built with vanilla JavaScript and the Open Library API, it provides cover art, book counts, and automatic sorting to make discovering and reading series easier.

## Features

- Search for book series by name
- Display all books in a series in reading order
- Show cover art for each book
- Display the total number of books in the series
- Automatic duplicate edition removal
- Responsive and lightweight interface
- No backend required

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- API: Open Library API
- Hosting: GitHub Pages

## How It Works

1. Enter the name of a book series.
2. The application queries the Open Library API for matching books.
3. Results are filtered and grouped into a series.
4. If series position metadata exists, books are sorted by their official order.
5. Duplicate editions are removed.
6. Covers, titles, and book counts are displayed to the user.

## Project Structure

```text
Series-Finder/
├── books.html
└── README.md
```

## Usage

### Search for a Series

1. Open the website.
2. Enter a series name such as:
   - Harry Potter
   - Percy Jackson
   - The Hunger Games
3. Press Search.
4. View all books in the series in reading order.

## Notes

- Results depend on data available through Open Library.
- Some series may have incomplete metadata, requiring fallback filtering methods.
- Different editions of the same book are automatically removed when possible.
- No user data is stored.

## Future Improvements

- Support for multiple reading orders
- Links to book information pages
- Better handling of spin-offs and companion novels
- Favorites and saved reading lists
- Enhanced filtering and sorting options
