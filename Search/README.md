# Search

Example based on imported csv files airbnb and titanic

## Airbnb

Only index  
`index=airbnb`

Property type  
`index=airbnb Neighbourhood=Queens "Property Type"=Apartment | fields - Beds`

Use where  
`index=airbnb Neighbourhood=Queens | where Price>40`

Pipe Remove fields  
`index=airbnb Neighbourhood=Queens | fields - Beds`

Pipe Search
`index=airbnb Neighbourhood=Queens | search pretty`

Pipe rename
`index=airbnb Neighbourhood=Queens | search pretty | rename Price as Cost`

## Titanic

`index=titanic`
