# simple_wireguard

### 1. Clone this repo  
```
git clone git@github.com:finzzz/simple_wireguard.git
```

### 2. Navigate to the directory  
```
cd simple_wireguard
```
          
### 3. Make executable
```
chmod +x simple_wg.sh
```
         
### 4. Find network interface name (usually eth0)
```
ifconfig
```  
         
### 5. Run (as root)
```
./simple_wg.sh init eth0
```
        
### 6. Add client
```
./simple_wg.sh add john 10.10.10.5
```
  
### 7. Follow the instruction. Done.
