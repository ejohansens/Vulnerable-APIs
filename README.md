Dataset of different vulnerable OpenAPI 3.0 specifications known to have BOLA vulnerabilities. 
Below is a list of each API and the endpoint corresponding to the BOLA vulnerability:
| API Name                 | Vulnerable Endpoints                                                                                          |
|--------------------------|---------------------------------------------------------------------------------------------------------------|
| VAmPI                    | `GET /books/v1/:book_title`  
|                          | `PUT /users/v1/:username/password`  
|                          | `PUT /users/v1/:username/email`  
|                          | `GET /users/v1/:username`  
|                          | `GET /users/v1`  
|                          | `GET /users/v1/_debug`                                                                                        |
| crAPI                    | `GET /identity/api/v2/vehicle/{vehicleId}/location`  
|                          | `GET /workshop/api/mechanic/mechanic_report`                                                                  |
| dvAPI                    | `GET api/getNote`                                                                                             |
| dvws                     | `/api/v2/notes/{ID}`                                                                                          |
| vulnerable-rest-api      | `GET /api/users/:name`  
|                          | `PUT /api/users/:id`                                                                                          |
| RESTaurant               | `GET /profile`                                                                                                |
| OWASP Juice Shop Vuln1   | `/rest/basket/{bid}`                                                                                          |
| OWASP Juice Shop Vuln2   | `/api/BasketItems`                                                                                            |
| Memos                    | `/api/v1/memo/{memoId}`                                                                                       |
| Capital                  | `DELETE /articles/{{slug}}/comments/{{commentId}}`                                                            |
| vuln-bank                | `GET /transactions/{account_number}`                                                                          |
| vapi                     | `GET /vapi/api1/user/{api1_id}`                                                                               |




Notice:

This repository is licensed under the GNU General Public License v3.0 (GPLv3).

However, it also includes OpenAPI 3 specifications released initially under:
- The Apache License 2.0 (in `/Apache`, see LICENSE file there)
- The MIT License (in `/MIT`, see LICENSE file there)
