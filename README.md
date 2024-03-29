# Google-Map-Multi-Marker

![image](https://user-images.githubusercontent.com/46887030/185583314-b0fef9fe-2c5c-4e3d-99d7-7f731842a25f.png)

Multiple Google Maps Markers is a simple project that helps to add multiple markers and filter them according to their status from the database and it uses multiple markers color to indicate different scenarios.

## Documentation

before starting to run the project you must have the apache server or [Xammp]() the recommended one. 

### Requirements

-   create your Google Map API Key
-   create your database
-   php v8 or later
-   Xampp or Apache server

#### DB Structure
```Sql
CREATE TABLE `locations` (
  `loc_id` int(11) NOT NULL,
  `name` longtext NOT NULL,
  `latitude` longtext NOT NULL,
  `longitude` longtext NOT NULL,
  `color` text NOT NULL,
  `status` text NOT NULL,
  `date` date NOT NULL
)
```

#### Color Pallete Used

-   for Employee we used [green-dot.png]()
-   for Client we used [orange-dot.png]()
-   for Car we used [red-dot.png]()

## Feedback and issues

Any issue and feedback from the app don't hesitate to make an issue

# Contributors

| [<img src="https://github.com/PrinceNiyonshuti.png" width="100px;"><br><sub><b>Niyonshuti Prince</b></sub>](https://github.com/PrinceNiyonshuti) |
| :------------------------------------------------------------------------------------------------------------------------ |

## Author

NIYONSHUTI Prince
