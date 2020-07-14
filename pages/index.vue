<template>
    <v-container><!-- Rooter Element -->
      <v-row
        justify="center"
        align="center"
        text-align="center"
      >
        <v-col>
          
        </v-col>
        <v-col cols="8">
          <h1>Site em processo de criação</h1>
        </v-col>

        <v-col cols="12" id="conteudo">
          <h3>
            Buscando sempre atender aos gostos e pedidos dos clientes, desenvolvo o que você precisa!
            Caso se interesse pelo serviço de programação entre em contato pelo botão.
          </h3>
          <v-btn href="https://api.whatsapp.com/send?phone=5514998803011&text=Olá!">
            <v-icon size="200%">mdi mdi-whatsapp</v-icon>
            <h4 class="ml-1">Whatsapp</h4>
          </v-btn>
        </v-col>
      </v-row>
    </v-container>
</template>

<style scoped>
  #conteudo {
    justify-content: center;
    align-content: center;
  }
</style>