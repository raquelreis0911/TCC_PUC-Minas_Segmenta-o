# TCC_PUC-Minas_Segmenta-o
Script com algoritmos de segmentação

# Capítulo 3: Processamento e tratamento dos dados

#Importação dos dados

install.packages("readxl")
library(readxl)
base_tcc = read_excel("/Users/raquel.reis/Documents/TCC/Banco de Dados - TCC - Raquel Reis Fernandes.xlsx")
head(base_tcc)

#Processamento dos dados

#P1 (gênero)
round(prop.table(table(base_tcc$P1))*100)

#P3 (região)
round(prop.table(table(base_tcc$P3))*100)

#P4 (faixa de renda individual mensal)
round(prop.table(table(base_tcc$P4))*100)

#P5_1 (cliente Santander)
round(prop.table(table(base_tcc$P5_1))*100)
#P5_2 (cliente Bradesco)
round(prop.table(table(base_tcc$P5_2))*100)
#P5_3 (Itaú)
round(prop.table(table(base_tcc$P5_3))*100)
#P5_4 (Banco do Brasil)
round(prop.table(table(base_tcc$P5_4))*100)
#P5_5 (Caixa)
round(prop.table(table(base_tcc$P5_5))*100)
#P5_6 (Banrisul)
round(prop.table(table(base_tcc$P5_6))*100)
#P5_7 (Sicredi)
round(prop.table(table(base_tcc$P5_7))*100)
#P5_8 (XP Investimentos)
round(prop.table(table(base_tcc$P5_8))*100)
#P5_9 (Original)
round(prop.table(table(base_tcc$P5_9))*100)
#P5_10 (Inter)
round(prop.table(table(base_tcc$P5_10))*100)
#P5_11 (Next)
round(prop.table(table(base_tcc$P5_11))*100)
#P5_12 (Neon)
round(prop.table(table(base_tcc$P5_12))*100)
#P5_13 (Nubank)
round(prop.table(table(base_tcc$P5_13))*100)
#P5_14 (Digio)
round(prop.table(table(base_tcc$P5_14))*100)
#P5_15 (C6 Bank)
round(prop.table(table(base_tcc$P5_15))*100)
#P5_16 (PicPay)
round(prop.table(table(base_tcc$P5_16))*100)
#P5_17 (Mercado Pago)
round(prop.table(table(base_tcc$P5_17))*100)
#P5_18 (PagSeguro / PagBank)
round(prop.table(table(base_tcc$P5_18))*100)
#P5_19 (Outros bancos ou instituições financeiras)
round(prop.table(table(base_tcc$P5_19))*100)

#P6 (banco que mais usa para pagamentos ou transferências)
round(prop.table(table(base_tcc$P6))*100)

#P7 (conta mais antiga)
round(prop.table(table(base_tcc$P7))*100)

#P8 (conta principal)
round(prop.table(table(base_tcc$P8))*100)

#P9 (banco da conta principal)
round(prop.table(table(base_tcc$P9))*100)

#P10 (classificação da renda)
round(prop.table(table(base_tcc$P10))*100)

#P11 (situação da moradia)
round(prop.table(table(base_tcc$P11))*100)

#P12_1 (possui casa própria)
round(prop.table(table(base_tcc$P12_1))*100)
#P12_2 (possui carro próprio)
round(prop.table(table(base_tcc$P12_2))*100)
#P12_3 (possui moto própria)
round(prop.table(table(base_tcc$P12_3))*100)
#P12_4 (não possui casa, carro ou moto próprios)
round(prop.table(table(base_tcc$P12_4))*100)

#P13_1 (nível de conhecimento sobre produtos de investimentos)
round(prop.table(table(base_tcc$P13_1))*100)
#P13_2 (nível de conhecimento sobre taxas de juros cobradas em diferentes empréstimos e financiamentos)
round(prop.table(table(base_tcc$P13_2))*100)
#P13_3 (benefícios de cartão de crédito)
round(prop.table(table(base_tcc$P13_3))*100)

#P14 (faixa de valor guardado e/ou investido)
round(prop.table(table(base_tcc$P14))*100)

#P15 (costume de parcelar compras)
round(prop.table(table(base_tcc$P15))*100)

#P16_1 (guardar dinheiro é impossível para mim ou para minha família)
round(prop.table(table(base_tcc$P16_1))*100)
#P16_2 (pegar empréstimo é uma boa opção em algumas situações)
round(prop.table(table(base_tcc$P16_2))*100)
#P16_3 (uso planilhas ou aplicativos de controle financeiro)
round(prop.table(table(base_tcc$P16_3))*100)
#P16_4 (anoto em um caderno o meu controle financeiro)
round(prop.table(table(base_tcc$P16_4))*100)
#P16_5 (frequentemente me desorganizo e esqueço de pagar alguma conta / despesa)
round(prop.table(table(base_tcc$P16_5))*100)
#P16_6 (guardo uma parte do meu dinheiro todo mês)
round(prop.table(table(base_tcc$P16_6))*100)
#P16_7 (tenho um plano de gastos / orçamento para as despesas do mês)
round(prop.table(table(base_tcc$P16_7))*100)
#P16_8 (tenho objetivos financeiros bem definidos para o futuro)
round(prop.table(table(base_tcc$P16_8))*100)
#P16_9 (todo mês tenho dinheiro suficiente para pagar todas as minhas despesas pessoais e as despesas fixas da casa)
round(prop.table(table(base_tcc$P16_9))*100)
#P16_10 (consigo guardar dinheiro)
round(prop.table(table(base_tcc$P16_10))*100)
#P16_11 (eu guardo dinheiro para atingir objetivos no futuro (educação dos meus filhos, comprar uma casa, aposentadoria, etc.))
round(prop.table(table(base_tcc$P16_11))*100)
#P16_12 (só vou começar a guardar dinheiro quando minha renda aumentar)
round(prop.table(table(base_tcc$P16_12))*100)
#P16_13 (possuo uma reserva financeira igual ou 3 vezes maior que o meu gasto mensal)
round(prop.table(table(base_tcc$P16_13))*100)
#P16_14 (eu calculo o valor de todo o meu patrimônio pelo menos uma vez por ano)
round(prop.table(table(base_tcc$P16_14))*100)
#P16_15 (prefiro que outra pessoa controle os meus ganhos e gastos (família, amigos, gerente do banco))
round(prop.table(table(base_tcc$P16_15))*100)
#P16_16 (não sou a melhor pessoa para controlar os meus ganhos e gastos)
round(prop.table(table(base_tcc$P16_16))*100)
#P16_17 (o quanto eu ganho é sempre maior do que o quanto eu gasto no mês)
round(prop.table(table(base_tcc$P16_17))*100)
#P16_18 (não consigo guardar dinheiro, mas não falta)
round(prop.table(table(base_tcc$P16_18))*100)
#P16_19 (o dinheiro que ganho acaba antes do fim do mês)
round(prop.table(table(base_tcc$P16_19))*100)
#P16_20 (defino um valor máximo que posso gastar por semana ou por mês)
round(prop.table(table(base_tcc$P16_20))*100)
#P16_21 (defino um valor máximo que posso gastar por tipo de gasto (ex: comida, aluguel, etc))
round(prop.table(table(base_tcc$P16_21))*100)
#P16_22 (costumo deixar de pagar alguma conta / despesa, porque não tenho dinheiro no momento)
round(prop.table(table(base_tcc$P16_22))*100)
#P16_23 (pedir crédito/empréstimos é algo negativo)
round(prop.table(table(base_tcc$P16_23))*100)
#P16_24 (não me preocupo em controlar os meus gastos)
round(prop.table(table(base_tcc$P16_24))*100)
#P16_25 (eu tento controlar meus gastos, mas no meio do mês acabo desistindo)
round(prop.table(table(base_tcc$P16_25))*100)
#P16_26 (não me interesso por assuntos financeiros)
round(prop.table(table(base_tcc$P16_26))*100)
#P16_27 (assuntos financeiros são muito complicados para mim)
round(prop.table(table(base_tcc$P16_27))*100)
#P16_28 (não possuo uma reserva de dinheiro para emergências)
round(prop.table(table(base_tcc$P16_28))*100)

#P2 (idade)
hist(base_tcc$P2, main = "Histograma Idade", ylab = "Frequência", xlab = "Idade")
summary (base_tcc$P2)
shapiro.test(base_tcc$P2)

# Capítulo 4: Criação dos modelos de Machine Learning

# Algoritmo k-médias

install.packages("readxl")
library(readxl)
base_tcc = read_excel("/Users/raquel.reis/Documents/TCC/Banco de Dados - TCC - Raquel Reis Fernandes.xlsx")
head(base_tcc)

install.packages("factoextra")
library(factoextra)

install.packages("ggplot2")
library(ggplot2)

#Retirando a coluna indivíduos

base_cluster = base_tcc[ ,-1] #retira a primeira coluna (ID_RESPOSTA).
base_cluster


#Clusterização k-means

#Usando a função fviz_nbclust do pacote factoextra, observa-se que o número ótimo de clusters é igual a 6.

fviz_nbclust(base_cluster, kmeans, method = "wss")

kmeans_cluster = kmeans(base_cluster, 4, iter.max=10, nstart=10)
kmeans_cluster

kmeans_cluster$size

base_cluster2 = cbind(base_cluster, cluster = kmeans_cluster$cluster)
base_cluster2 = cbind(base_cluster2, id = base_tcc$ID_RESPOSTA)
base_cluster2

#Exportando a base_cluster2
setwd("/Users/raquel.reis/Documents/TCC")
write.csv(base_cluster2, "clusters_k_medias")

#Visualização dos clusters

fviz_cluster(kmeans_cluster, data=base_cluster,
             palette = c("#2E9FDF", "#00AFBB", "#E7B800", "#FC4E07"),
             ellipse.type="euclid",
             star.plot=TRUE,
             repel=TRUE,
             ggtheme=theme_bw()
)

# Algoritmo de agrupamento hierárquico

distancia = dist(base_cluster, method="euclidean")
as.matrix(distancia)

cluster_aglomerativo = hclust(d=distancia,method="ward.D")

library("factoextra")
fviz_dend(cluster_aglomerativo, cex=0.10)

plot(cluster_aglomerativo)

rect.hclust(cluster_aglomerativo, k=4)

vetor_cluster = cutree(cluster_aglomerativo,4)
vetor_cluster

base_cluster_aglomerativo = data.frame(base_tcc, cluster=vetor_cluster)
head(base_cluster_aglomerativo)

# Algoritmo de agrupamento baseado em modelos

install.packages("readxl")
library(readxl)
base_tcc = read_excel("/Users/raquel.reis/Documents/TCC/Banco de Dados - TCC - Raquel Reis Fernandes.xlsx")
head(base_tcc)

#Retirando a coluna indivíduos

base_cluster = base_tcc[ ,-1] #retira a primeira coluna (ID_RESPOSTA).
base_cluster

install.packages("mclust")
library(mclust)

cluster_mclust = Mclust(base_cluster)
cluster_mclust

plot(cluster_mclust, what = "BIC", ask=FALSE)

#Visualização dos clusters

install.packages("ggplot2")
library(ggplot2)
mclusters = factor(predict(cluster_mclust)$classification)
mclusters
base_cluster_baseado_modelo = data.frame(base_tcc, mclusters)
base_cluster_baseado_modelo

#Exportação das bases

install.packages("xlsx")
library(xlsx)
write.xlsx(base_cluster2, file="base_cluster_k_medias.xlsx")
write.xlsx(base_cluster_aglomerativo, file="base_cluster_aglomerativo.xlsx")
write.xlsx(base_cluster_baseado_modelo, file="base_cluster_modelos.xlsx")
