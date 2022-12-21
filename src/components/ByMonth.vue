<template>
  <v-container fluid>
    <v-row>
        <v-col>
            <!-- Selectors for month and year, and a submit button -->
            <v-select
                :items="items"
                v-model="month"
                label="Mês"
            ></v-select>

        </v-col>
        <v-col>
            <v-btn icon color="success">
                <v-icon color="white">mdi-check</v-icon>
            </v-btn>

        </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    data() {
        return {
            month: 'Janeiro',
            items:[
                'Janeiro',
                'Fevereiro',
                'Março',
                'Abril',
                'Maio',
                'Junho',
                'Julho',
                'Agosto',
                'Setembro',
                'Outubro',
                'Novembro',
                'Dezembro'
            ]
        }
    },
}
</script>

<style>

</style>