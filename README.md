# react-tour-v2

The Tour App is a web application built on React.js that allows users to browse and manage a list of tours fetched from a REST API. The app provides an intuitive and user-friendly interface for users to interact with tour data effectively.

Features:

    Fetching Data from REST API:
    The application leverages the power of React.js to communicate with a RESTful API and retrieve a list of tours. This API serves as the backend and provides the tour data in JSON format.

    Displaying Tours:
    Once the tour data is fetched from the API, the application dynamically renders and displays the tours on the user's screen. Each tour is presented in a visually appealing manner with relevant information such as tour name, destination, infomation, and price.

    Hiding Specific Tours:
    To enhance user experience and customization, the app allows users to hide specific tours that they are not interested in. This feature gives users the flexibility to personalize their tour list and only see the tours that pique their interest.

    Show/Hide Tour Info:
    Users can toggle the visibility of detailed tour information for each tour. This feature provides a compact overview of tours by showing essential details initially. When a user wants to explore more information about a specific tour, they can click a button to reveal additional details, such as tour itinerary, highlights, and other relevant details.

    Refreshing Tours:
    In case the user hide all tours, the application automatically detects if the tours' list becomes empty. When this occurs, the app show a button to user that triggering a new API call to fetch fresh tour data. This ensures that the user always has access to the latest list of available tours, even after customizing the visibility of individual tours.
