<h2>Subscan</h2>
 
<h3>Configurações: </h3>
   <p> git clone https://github.com/luanfatec/subscan.git </p>
   <p> cd subscan/ </p>
   <p> chmod +x subscan </p>
   
     
    Sintaxe básica
        ./subscan exemple.com <option> <nomearquivo> <subdomains-words>
        
    Exemplo:
        root@mysystem# ./subscan exemple.com --http filename wordlist
    
         --http          Buscar subdominios sem a segurança TLS.
    
         --http          Buscar subdominios com a segurança TLS.
