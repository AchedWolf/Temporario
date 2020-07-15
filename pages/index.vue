<template>
  <v-container class="text-center justify-center align-center"><!-- Rooter Element -->
    <v-row
      align="center"
      justify="end"
    > 
      <v-col cols="4">
        <v-row justify="end">
          <v-img
            class="ml-2 text-center"
            src="/Imagens/meu-logo.png"
            max-height="100"
            max-width="100"
          />
        </v-row>
      </v-col> 
  
      <v-col cols="8">
        <v-row 
          justify="start"
          class="pl-2 pl-sm-16 ml-sm-16"
        >
          <h1>Site em processo de criação</h1>
        </v-row>
      </v-col>

      <v-col cols="12">  
        <h3>
          Buscando sempre atender aos gostos e pedidos dos clientes, desenvolvo o que você precisa!<br />
          Ultimo serviço: <a href="https://triskeleletrificacao.com.br">triskeleletrificacao.com.br</a><br />
          Caso se interesse pelo serviço de programação entre em contato pelo botão.
        </h3>
              
        <v-btn 
          id="botao" 
          href="https://api.whatsapp.com/send?phone=5514998803011&text=Olá, gostaria de fazer um orçamento para meu projeto."
          class="mt-3"
        >
          <v-icon size="200%" class>mdi mdi-whatsapp</v-icon>
          <h4 class="ml-1">Whatsapp</h4>
        </v-btn>
      </v-col>
    </v-row>  
  </v-container>
</template>

<style scoped>
  #botao {
    background-color: #34af23;
    color: white;
  }
</style>