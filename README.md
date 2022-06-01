# Molecular_fingerprint-Clustering

<explanation>
  I used Fingerprint method in RDKFingerprint(x) function, which return the bitvector about its fingerprint. Then, I use tanimoto similarity to calculate the distance between them. I calculate the distance by 1-(tanimoto similarity). By using the distance, I use Butina clustering method fo clustering. Then, I see the distribution of my clustered results to know that I effectively cluster the data. Lastly, I use the TSNE function for dimension reduction, and plot them. I colored TOP 9 cluster, and other things are colored as gray. 
