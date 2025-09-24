# pokeapi

# @Headers("Content-Type: application/json")
# @POST("graphql/v1beta")

# Base url: https://beta.pokeapi.co/

# GraphQL query: 
            """query {
              pokemon_v2_pokemon(limit: 30) {
                id
                name
              }
            }"""