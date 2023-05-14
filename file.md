# Cabinet 

| Endpoint                   | Method | Description                                               |
|----------------------------|--------|-----------------------------------------------------------|
| `/api/v1/cabinet`          | POST   | Create a new cabinet                                      |
| `/api/v1/cabinet`          | GET    | Get all cabinets                                          |
| `/api/v1/cabinet/{id}`     | GET    | Get a cabinet by ID                                       |
| `/api/v1/cabinet/{id}`     | DELETE | Delete a cabinet by ID                                    |
| `/api/v1/cabinet/{id}`     | PUT    | Update a cabinet by ID                                    |
| `/api/v1/cabinet/{id}/medecin` | GET    | Get medecins in a cabinet by cabinet ID               |

# Medecin

| Endpoint                             | Method | Description                                   |
|--------------------------------------|--------|-----------------------------------------------|
| `/api/v1/medcin/{cabinetId}/cabinet` | POST   | Create a new medecin for a specific cabinet   |
| `/api/v1/medcin/{medecinId}`          | DELETE | Delete a medecin by ID                       |
| `/api/v1/medcin`                      | GET    | Get all medecins                             |
| `/api/v1/medcin/{medecinId}`          | GET    | Get a medecin by ID                          |
| `/api/v1/medcin/{medecinId}`          | PUT    | Update a medecin by ID                       |


# Disponibilite

| Endpoint                                              | Description                                                              |
| ----------------------------------------------------- | ------------------------------------------------------------------------ |
| `POST /api/v1/disponibilite/medecin/{medecinId}`       | Creates a new `Disponibilite` for a specific `Medecin`.                  |
| `GET /api/v1/disponibilite/{disponibiliteId}`          | Retrieves a specific `Disponibilite` by ID.                              |
| `PUT /api/v1/disponibilite/{disponibiliteId}`          | Updates a specific `Disponibilite` by ID.                                |
| `DELETE /api/v1/disponibilite/{disponibiliteId}`       | Deletes a specific `Disponibilite` by ID.                                |
| `GET /api/v1/disponibilite/medecin/{medecinId}`        | Retrieves all `Disponibilite` records associated with a specific `Medecin`. |
