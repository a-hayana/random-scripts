mode <- function(x) {
  ux <- unique(x) #extrai os valores únicos
  tab <- tabulate(match(x, ux)) #recomenda-se a busca para entender a funcionalidade dessas funções
  ux[tab == max(tab)] #captura os valores com maior frequência, note que pode ser mais que um
}

mode(x)
