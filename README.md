# [Keerthi Sandhya] - Our Wedding Website

Welcome to our cinematic wedding website! This site is designed to share all the important details about our special day with our beloved family and friends. It features image galleries, video invitations, event schedules with location maps, and even a live stream option for those who can't join us in person.

The website is built with a focus on a modern, elegant, and user-friendly experience, following Google Material Design guidelines and utilizing a beautiful pastel color palette. It's designed to be hosted easily and for free on GitHub Pages.

## Features

*   **Cinematic Hero Section:** A striking full-screen image/video background with a personalized welcome and countdown.
*   **Smooth Navigation:** Intuitive sticky navigation for easy access to all sections.
*   **Our Story/Invitation Video:** Dedicated section to share our journey and an embedded video invitation.
*   **Moments & Gallery:** A carousel (placeholder for a JS library like Swiper.js) and a grid gallery to showcase our cherished photos.
*   **Detailed Event Schedule:** Clear breakdown of ceremony, reception, and other events with dates, times, and venues.
*   **Interactive Location Map:** Embedded Google Map for easy navigation to event locations.
*   **Live Stream Integration:** Seamless embedding of YouTube or Facebook Live streams for remote guests.
*   **RSVP Functionality:** Link to a Google Form or external RSVP service.
*   **Responsive Design:** Optimized for viewing on desktops, tablets, and mobile devices.
*   **Modern UI:** Pastel color scheme, clean typography (Google Fonts: Roboto, Playfair Display), and subtle Material Design-inspired shadows.
*   **Free Hosting:** Easily deployable on GitHub Pages.

## Technologies Used

*   **HTML5:** Structure and content.
*   **CSS3:** Styling, including responsive design and Material Design aesthetics.
*   **JavaScript (ES6+):** For interactive elements like smooth scrolling (and placeholders for carousel/countdown logic).
*   **Google Fonts:** For elegant typography (`Roboto`, `Playfair Display`).
*   **Font Awesome:** For icons (e.g., calendar, map pins).
*   **YouTube/Vimeo Embeds:** For video content.
*   **Google Maps Embed API:** For location maps.
*   **GitHub Pages:** For free web hosting.

## Setup and Deployment (GitHub Pages)

Follow these steps to get your wedding website live on GitHub Pages:

1.  **Create a GitHub Repository:**
    *   Go to [GitHub](https://github.com/) and create a new repository.
    *   **For a User Page (e.g., `yourusername.github.io`):** Name the repository exactly `yourusername.github.io` (replace `yourusername` with your GitHub username). Your site will be live at `https://yourusername.github.io`.
    *   **For a Project Page (e.g., `wedding-website`):** Name the repository `wedding-website` (or any other name). Your site will be live at `https://yourusername.github.io/wedding-website`.

2.  **Clone the Repository (Optional, but Recommended):**
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

3.  **Add Your Website Files:**
    *   Place `index.html`, `style.css`, and `script.js` directly into the root of your repository.
    *   Create an `images/` folder for your wedding photos (e.g., `images/hero-bg.jpg`, `images/photo1.jpg`).

4.  **Customize Content:**
    *   Open `index.html` and update:
        *   `[Couple's Names]` with your names.
        *   `Wedding Date: Day, Month XX, Year` with your actual wedding date.
        *   Replace placeholder image URLs (`https://via.placeholder.com/...`) with paths to your actual images (e.g., `images/your-hero-image.jpg`).
        *   Update YouTube/Vimeo `iframe` `src` attributes with your video IDs.
        *   Generate and embed your specific Google Maps `iframe` code for event locations.
        *   Update event details (date, time, location).
        *   Set your RSVP Google Form link or email address.
    *   Open `script.js` and update `actualWeddingDate` with your exact wedding date and time for the countdown.

5.  **Commit and Push to GitHub:**
    ```bash
    git add .
    git commit -m "Initial wedding website deployment and content customization"
    git push origin main # Or 'master', depending on your default branch
    ```

6.  **Enable GitHub Pages:**
    *   Navigate to your repository on GitHub.
    *   Click on **Settings**.
    *   In the left sidebar, click **Pages**.
    *   Under "Build and deployment," ensure **"Deploy from a branch"** is selected for "Source."
    *   For "Branch," select your main branch (`main` or `master`) and choose `/ (root)` for the folder.
    *   Click **Save**.
    *   GitHub will now build and deploy your website. This process may take a few minutes. Once complete, your site's URL will be displayed in the "GitHub Pages" section.

## Customization and Further Enhancements

*   **Image Carousel:** The current carousel in `index.html` is a placeholder. For a fully functional and animated carousel, consider integrating a JavaScript library like [Swiper.js](https://swiperjs.com/):
    1.  Add `<link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">` to your `<head>`.
    2.  Add `<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>` before your `script.js` in `<body>`.
    3.  Adjust the HTML structure of your carousel images as per Swiper.js documentation.
    4.  Initialize Swiper in `script.js` (uncomment the provided placeholder code).
*   **Countdown Timer:** Implement the full countdown logic in `script.js` to display days, hours, minutes, and seconds until the wedding.
*   **Custom Domain:** GitHub Pages supports custom domains. Refer to the [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) for instructions.
*   **More Sections:** Add more sections like "Our Bridal Party," "Accommodation," "Registry," etc., as needed.
*   **Animations:** Introduce more subtle CSS animations or JavaScript-based scroll animations for a more dynamic "cinematic" feel.
*   **Favicon:** Add a `favicon.ico` file to the root and link it in your `index.html`'s `<head>`.

## License

This project is open-source and available under the [MIT License](LICENSE.md) (or specify your preferred license).

---