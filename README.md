# wns-deploy
continuous deployment 104

# Enter server
ssh wns_student@remote12-0921.wns.wilders.dev -p 2269
# Password on excel sheet 🤫

# Execute repo local (changed port to 8002 because 8000 was already used on my side)
GATEWAY_PORT=8002 docker-compose up
# Accessible via 
http://localhost:8001/

