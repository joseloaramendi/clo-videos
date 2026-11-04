# Entradas con QR — evento (30 invitados)

- `entradas.pdf`: las 30 entradas listas para imprimir (12 por hoja A4).
- `png/entrada-NN.png`: cada QR por separado, para mandar por WhatsApp o mail.
- `codigos.csv`: número y código de cada entrada (completá la columna nombre si querés).
- `control-ingreso.html`: página de control de ingreso (publicada como Artifact en claude.ai). En la pestaña "Entradas" se carga el nombre de cada cliente y se descarga su entrada individual como imagen (ver `ejemplo-entrada.png`).

Cada QR contiene un código único (`EVNN-XXXXXXXX`). La página de control marca cada código como usado
en una lista compartida; un segundo escaneo muestra "YA INGRESÓ" con la hora del primero.
