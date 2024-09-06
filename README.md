# MyView

MyView is a social platform that combines the best of MySpace and Reddit. It’s a place where users can express themselves, connect with others, and share content in a customizable and community-driven environment

## Features

* **Profiles:** Create your personalized profile with a custom bio, profile picture, and background.

* **Posts and Comments:** Share your thoughts, images, and links with the community. Engage in discussions through comments.

* **Customization:** Customize your profile layout, colors, and fonts to make it uniquely yours.

* **Communities (a.k.a. “Views”):** Join or create Views—special interest groups where users can discuss specific topics. Whether it’s music, coding, or cat memes, there’s a View for everyone.

## Installation

1. Clone the Repository:
```bash
git clone https://github.com/your-username/MyView.git
```
2. Navigate to the Project Directory:
```bash
cd MyView
```
3. Install Dependencies:
```bash
bundle install
```
4. Database Setup:
* Make sure you have PostgreSQL installed
* Create the database and run migrations:
```bash
bundle exec rails db:create
bundle exec rails db:migrate
```
5. Start the Server:
```bash
bundle exec rails server
```
6. Access MyView: Open your web browser and visit `http://localhost:3000`

## Contributing
Contributions are welcome! If you’d like to improve MyView, feel free to submit pull requests or open issues.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
