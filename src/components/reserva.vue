<template>
   <div>
    <div id="index">
      <v-app>
        <v-main>
          <v-container class="grey lighten-5 mb-6">
              <h3>Reservar</h3>
              <v-row no-gutters style="height: 150px;" mb="6">
                  <v-col cols="12" sm="4">
                      <v-text-field
                      label="Nombre"
                      required
                      outlined>
                      </v-text-field>
                  </v-col>

                  <v-col cols="6" sm="2">
                      <v-text-field
                      label="Fecha"
                      value=""
                      type="date"
                      append-icon="mdi-calendar"
                      outlined
                      >
                      </v-text-field>
                  </v-col> 

                  <v-col cols="6" sm="2">
                      <v-text-field
                      label="Desde"
                      value=""
                      type="time"
                      append-icon="mdi-clock"
                      outlined
                      >
                      </v-text-field>
                  </v-col>

                  <v-col cols="6" sm="2">
                      <v-text-field
                      label="Hasta"
                      value=""
                      type="time"
                      append-icon="mdi-clock"
                      outlined
                      >
                      </v-text-field>
                  </v-col>
                  <v-col cols= "1"></v-col>
                  <v-col cols="1">
                      <v-btn
                      depressed
                      elevation ="1"
                      color="success"
                      fab>
                        <v-icon>mdi-check</v-icon>
                      </v-btn>
                  </v-col>
              </v-row>
          </v-container>
        </v-main>
      </v-app>
    </div>
  </div>
</template>
<script>
  export default {
    name: 'reserva',
  }
</script>