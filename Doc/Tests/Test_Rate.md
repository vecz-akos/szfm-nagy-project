| Feature           | Description                                                                    | Steps To Execute                                  | Test Data / Input | Expected Results                                   |   |   |   |   |   |
|-------------------|--------------------------------------------------------------------------------|---------------------------------------------------|-------------------|----------------------------------------------------|---|---|---|---|---|
| Back to category  | User can back to the category page                                             | 1. Open a sample <br> 2. Click the category link  | N/a               | Correct link is generated                          |   |   |   |   |   |
| Rate01            | User can rate a new sample                                                     | 1. Select a value <br> 2. Click Send!             | 1, 2, 3, 4, 5     | Succes page and save to database                   |   |   |   |   |   |
| Rate02            | User cannot rate already rated sample                                          | Go to a sample                                    | N/a               | User can see the older rate.                       |   |   |   |   |   |
| Rate03            | User get an error message, if user dont fill the input field.                  | 1. Go to a sample <br> 2. Click Send!             | N/a               | User get an error message, about the missing data  |   |   |   |   |   |
| Link              | Load sample page with category number id in URL, instead of the default string | 1. Go to a link localhost/rate/1/1                | N/a               | Load the correct page                              |   |   |   |   |   |
| Image missing     | If sample hasent got image, the page should not crash.                         | Go to a sample                                    | N/a               | There is no image, but the site doesent crash.     |   |   |   |   |   |
| Image not missing | If sample has got image, the page should appeared.                             | Go to a sample page                               | N/a               | There is a nice imgage about the sample.           |   |   |   |   |   |
| UI on mobile      | Responsiveness                                                                 | 1. Go to a sample page <br> 2. Check the results. | N/a               | On mobile devices every useful information appear. |   |   |   |   |   |
| UI on table       | Responsiveness                                                                 | 1. Go to a sample page <br> 2. Check the results. | N/a               | On tablet devices every useful information appear. |   |   |   |   |   |
| UI on smart watch       | Responsiveness                                                                 | 1. Go to a sample page <br> 2. Check the results. | N/a               | On smart watch devices every useful information appear. |   |   |   |   |   |