## Lab 1: Basic LAN Network (Packet Tracer)

### Objective
Build a simple LAN network and verify connectivity between two PCs.

---

## Network Topology
![Topology](lab1-simple-lan/screenshots/topology.png)

---

## IP Configuration
PC0: 192.168.1.1  
PC1: 192.168.1.2  

![IP Configuration](lab1-simple-lan/screenshots/ip-config.png)

---

## Connectivity Test
Ping between hosts:

![Ping Result](lab1-simple-lan/screenshots/ping.png)

---

## Result
- Devices are in the same subnet (192.168.1.0/24)
- Successful ICMP communication between hosts
- Switch forwards frames correctly at Layer 2


## Result

The LAN network is fully operational:
- Both PCs are in the same subnet (192.168.1.0/24)
- ICMP ping is successful
- Switch correctly forwards traffic between hosts


## Лабораторная работа 2: Маршрутизатор и межсетевое взаимодействие

### Цель
Настроить маршрутизацию между двумя различными локальными сетями с помощью маршрутизатора.

---

## Сетевая топология
![Топология](lab1-simple-lan/screenshots/topology2.png)

---

## Конфигурация маршрутизатора
![Конфигурация маршрутизатора](lab1-simple-lan/screenshots/routerconfig.png)

---

## Конфигурация PC0
![IP-адрес PC0](lab1-simple-lan/screenshots/ip-configpc0.png)

---

## Конфигурация PC1
![IP-адрес PC1](lab1-simple-lan/screenshots/ip-configpc1.png)

---

## Проверка подключения
![Результат пинга](lab1-simple-lan/screenshots/ping2.png)

---

## Результат
- Настроены две отдельные локальные сети
- Маршрутизатор успешно выполняет межсетевую маршрутизацию
- ICMP-связь между подсетями работает
