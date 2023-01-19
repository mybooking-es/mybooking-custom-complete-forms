# MyBooking custom complete form

MyBooking Reservation Engine and Theme have defined a simple complete/checkout form. 
It includes the basic fields in order to keep customer full name and contact details
like phone number and e-mail address.

Sometimes the customer requires extra fields. MyBooking Reservation Engine allows two ways
to define them:

1. Creating a child theme and build a custom mybooking-plugin-complete.php 
2. Use an extension plugin like https://wordpress.org/plugins/header-footer-code-manager/ or
https://wordpress.org/plugins/custom-css-js/ and create one document for each
language.

This project holds a different set of custom template form with the most common used fields 
ready to use. Just create a document the plugin described and insert the code.

## Pre-made forms

These are forms ready to use with mybooking theme or other theme.

In mybooking-theme folder there are examples to use with mybooking theme.
In mybooking-plugin folder there are examples to use with any theme.

### renting-complete-standard-rentacar
 
Includes the following fields:

- Driver date of birth
- Number of places
- Customer address
- Flight number
- Destination accommodation

### renting-complete-flight

Includes the flight number instead of alternative phone number

### renting-complete-places

Includes the number of places instead of alternative phone number

## Fields

Here there is a list of all fields that you can use to include in your custom forms.

| Campo                                               | Descripción                              | Detalle |                                                                              |
| --------------------------------------------------- | ---------------------------------------- | ------- | ---------------------------------------------------------------------------- |
| customer_name                                       | Nombre del cliente                       | String(40)  | Obligatorio                                                                  |
| customer_surname                                    | Apellidos del cliente                    | String(40)  | Obligatorio                                                                  |
| customer_email                                      | Email del cliente                        | String(40)  | Obligatorio                                                                  |
| customer_phone                                      | Teléfono alternativo del cliente         | String(15)  | Opcional                                                                     |
| comments                                            | Comentarios                              | String  | Opcional                                                                     |
| street                                              | Dirección (calle)                        | String(60)  | Opcional                                                                     |
| number                                              | Dirección (número)                       | String(10)  | Opcional                                                                     |
| complement                                          | Dirección (complemento)                  | String(20)  | Opcional                                                                     |
| city                                                | Dirección (ciudad)                       | String(60)  | Opcional                                                                     |
| state                                               | Dirección (provincia o estado)           | String(60)  | Opcional                                                                     |
| country                                             | Dirección (país)                         | String(50)  | Opcional                                                                     |
| zip                                                 | Dirección (código postal)                | String(10)  | Opcional                                                                     |
| fligth_airport_origin                               | Aeropuerto origen                        | String(100)  | Opcional                                                                     |
| flight_company                                      | Compañía aérea                           | String(80)  | Opcional                                                                     |
| flight_number                                       | Número de vuelo                          | String(10)  | Opcional                                                                     |
| flight_time                                         | Hora prevista de llegada                 | String(5)  | Opcional                                                                     |
| fligth_airport_destination                          | Aeropuerto destino                       | String(100)  | Opcional                                                                     |
| flight_company_departure                            | Compañía aérea regreso                   | String(80)  | Opcional                                                                     |
| flight_number_departure                             | Número de vuelo regreso                  | String(10)  | Opcional                                                                     |
| flight_time_departura                               | Hora prevista de regreso                 | String(5)  | Opcional                                                                     |
| driver_name                                         | Nombre del conductor                     | String(40)  | Opcional                                                                     |
| driver_surname                                      | Apellidos del conductor                  | String(40)  | Opcional                                                                     |
| driver_document_id                                  | Documento conductor                      | String(50)  | Opcional                                                                     |
| driver_date_of_birth                                | Fecha nacimiento conductor               | dd/mm/yyyy  | Opcional                                                                     |
| driver_driving_license_number                       | Número permiso conducir conductor        | String(50)  | Opcional                                                                     |
| driver_driving_license_date                         | Fecha permiso conducir                   | dd/mm/yyyy  | Opcional                                                                     |
| driver_driving_license_country                      | País permiso conducir                    | String(50)  | Opcional                                                                     |
| driver_driving_license_expiration_date              | Fecha caducidad permiso conducir         | dd/mm/yyyy  | Opcional                                                                     |
| additional_driver_1_name                            | Nombre del conductor                     | String(40)  | Opcional                                                                     |
| additional_driver_1_surname                         | Apellidos del conductor                  | String(40)  | Opcional                                                                     |
| additional_driver_1_document_id                     | Documento conductor                      | String(50)  | Opcional                                                                     |
| additional_driver_1_date_of_birth                   | Fecha nacimiento conductor               | dd/mm/yyyy  | Opcional                                                                     |
| additional_driver_1_driving_license_number          | Número permiso conducir conductor        | String(50)  | Opcional                                                                     |
| additional_driver_1_driving_license_date            | Fecha permiso conducir                   | dd/mm/yyyy  | Opcional                                                                     |
| additional_driver_1_driving_license_country         | País permiso conducir                    | String(50)  | Opcional                                                                     |
| additional_driver_1_driving_license_expiration_date | Fecha caducidad permiso conducir         | dd/mm/yyyy  | Opcional                                                                     |
| additional_driver_2_name                            | Nombre del conductor                     | String(40)  | Opcional                                                                     |
| additional_driver_2_surname                         | Apellidos del conductor                  | String(40)  | Opcional                                                                     |
| additional_driver_2_document_id                     | Documento conductor                      | String(50)  | Opcional                                                                     |
| additional_driver_2_date_of_birth                   | Fecha nacimiento conductor               | dd/mm/yyyy  | Opcional                                                                     |
| additional_driver_2_driving_license_number          | Número permiso conducir conductor        | String(50)  | Opcional                                                                     |
| additional_driver_2_driving_license_date            | Fecha permiso conducir                   | dd/mm/yyyy  | Opcional                                                                     |
| additional_driver_2_driving_license_country         | País permiso conducir                    | String(50)  | Opcional                                                                     |
| additional_driver_2_driving_license_expiration_date | Fecha caducidad permiso conducir         | dd/mm/yyyy  | Opcional                                                                     |