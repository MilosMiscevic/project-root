# Koristimo Go baznu sliku
FROM golang:1.20-alpine

# Postavimo radni direktorijum
WORKDIR /app

# Kopiramo sve Go fajlove u kontejner
COPY . .

# Instaliramo zavisnosti i kompajliramo aplikaciju
RUN go build -o main .

# Pokrećemo aplikaciju
CMD ["./main"]
