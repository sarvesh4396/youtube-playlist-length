# Youtube Playlist Length Calculator

This is a simple web-app that calculates the length of a YouTube playlist.

It also shows the length of a playlist at increased speeds of 1.25x, 1.50x, 1.75x and 2x.

It is built with [FastApi](https://fastapi.tiangolo.com/) and deployed on [Vercel](https://vercel.com/)

## Setup

1. Clone the repository
2. Make a virtualenv

    ```sh
    virtualenv 3.8.5
    ```

3. Install requirements

    ```sh
    pip install -r requirements.txt
    ```

4. make .env file

5. Get your [Youtube Api Key](https://developers.google.com/youtube/v3/getting-started) and add it in `.env`

    ```env
    KEY=your-api-key
    ```

6. Run it

    ```sh
    python app.py
    ```

7. It's done.
