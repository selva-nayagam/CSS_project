# SelvaGym - CSS Project

A responsive gym website template built with HTML, CSS, Bootstrap, and jQuery.

## Features

- Responsive design
- Bootstrap-based layout
- Multiple pages (Home, Why Us, Trainers, Contact)
- Image carousel/slider
- Contact form
- Trainer profiles

## Prerequisites

- Java 21 or higher
- Maven 3.6 or higher

## Building the Project

To build the project, run:

```bash
mvn clean package
```

This will create a WAR file in the `target` directory.

## Running the Application

To run the application locally using the embedded Jetty server:

```bash
mvn jetty:run
```

The application will be available at: [http://localhost:8080](http://localhost:8080)

Press `Ctrl+C` to stop the server.

## Project Structure

```
CSS_project/
├── src/
│   └── main/
│       └── webapp/
│           ├── index.html      # Home page
│           ├── why.html        # Why Us page
│           ├── trainer.html    # Trainers page
│           ├── contact.html    # Contact page
│           ├── css/            # Stylesheets
│           ├── js/             # JavaScript files
│           ├── images/         # Images and icons
│           └── WEB-INF/        # Web application configuration
├── pom.xml                     # Maven configuration
└── README.md                   # This file
```

## Deployment

To deploy to a servlet container (Tomcat, Jetty, etc.):

1. Build the WAR file: `mvn clean package`
2. Copy the WAR file from `target/Sample_css_template-0.0.1-SNAPSHOT.war` to your servlet container's deployment directory

## Technology Stack

- **Frontend**: HTML5, CSS3, Bootstrap 4, jQuery
- **Build Tool**: Maven
- **Packaging**: WAR (Web Application Archive)
- **Server**: Compatible with any Servlet 3.1+ container

## License

Design by [Free Html Templates](https://html.design/)
