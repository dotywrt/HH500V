# HH500V

## Modem Control GPIOs

| Function        | GPIO Controller | GPIO Number | Active Level | Default State | Description                         |
|----------------|----------------|------------|--------------|--------------|-------------------------------------|
| Modem Power    | tlmm           | 30         | HIGH         | HIGH         | Powers ON modem when HIGH           |
| Modem Reset    | tlmm           | 29         | HIGH         | HIGH         | Reset line (pulse LOW to reset)     |
| Modem EDL      | tlmm           | 46         | HIGH         | HIGH         | Emergency Download Mode (EDL)       |
