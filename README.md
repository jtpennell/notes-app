# NotesApp

A simple Ruby on Rails application that lets users save notes written in Markdown with a live preview before saving.

## Ruby Version

- Ruby 3.4.4

## System Dependencies

- Rails 7.1.5.1
- SQLite3 (default development database)
- Tailwind CSS (via Rails gem)
- Marked.js (for client-side Markdown rendering)

## Configuration

- No extra configuration required beyond standard Rails setup.
- Tailwind CSS is included for styling.
- Marked.js is loaded via CDN in `application.html.erb` for Markdown preview

## Database Setup

```bash
bin/rails db:setup
bin/rails db:migrate
```
## Host / Testing
```bash
bundle install
bin/rails server -p 3000
```