1. mkdir Weekly_Task_3 --> nano main.tf --> cat main.tf ![1](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/d83ed70f-12b7-416d-a5c2-50dc976e9019)


2. nano install.sh --> cat install.sh  ![2](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/fbc7f875-1cf8-4609-a090-45be8dd4acad)


3. install terraform --> terraform --version ![3](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/3f961d4f-f9cb-46fb-bdb5-391d53d35310)


4. terraform init --> terraform plan ![4](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/000f92b7-a49e-41de-9dd1-bfdbcb16bee7)


5. terraform apply  ![5](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/1e82dac1-62fb-48a6-b400-4e86f23a4733)
![5 1](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/7057b65d-8b81-4ec1-b45c-2b723ddbc687)
 

6. Now goto EC2 --> Instance is created and running ![6](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/2991186c-0c0c-4ee1-80b3-83ea2ae24528)


7. Connect with PrometheusInstance --> docker –version (to check user-data install docker)  ![7](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/280655d9-1752-48dd-9c9e-3bdbd5998121)


8. nano docker-compose.yml --> cat docker-compose.yml  ![8](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/440088b6-25a6-48c5-9518-bf460c138013)


9. nano prometheus.yml  --> cat prometheus.yml ![9](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/95855da7-a6db-4cc8-a904-2c0e726f86ba)


10 docker-compose up –d --> docker ps –a ![10](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/f41d74de-ee40-4674-810d-adb137df8da2)


11. docker images  ![11](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/07b7d104-2e60-4ead-9231-a6a89137805c)


12. node-exporter:9100 --> prometheus:9090 --> both are working ![12](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/1a313bac-df50-4fb8-ac76-a4a4097e9605)


13. Grafana:3000 --> username: admin --> password: admin --> setup dashboard --> high CPU usage: send notification  ![13](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/8c79484a-7649-4c12-98ae-c1c212a9dc81)
![13 1](https://github.com/GauravDevOps711/Weekly-Task2-/assets/135973657/acdd44ba-a03d-4f7c-bb54-504dae5dcd57)

