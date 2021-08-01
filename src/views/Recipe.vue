<template>
    <v-container>
        <v-row>
            <h1>Recipe: {{ name }}</h1>
            <v-col>
                Ingredients:
            </v-col>
            <v-col>
                Available Ingredientes:

            </v-col>
            <v-col cols='12'>
                <ul>
                    <li>Servings: </li>
                    <li>
                        Missing ingredients:
                        <ol>
                            <li>Ingredient 1</li>
                        </ol>
                    </li>
                </ul>
                Missing ingredients:
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    data() {
        return {
            name: 'Cake',
        }
    },
}
</script>