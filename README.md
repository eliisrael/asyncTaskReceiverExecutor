# asyncTaskReceiverExecutor

This is typescript based code for a task receiver/executor

First service receives a task and stores it on a tasks queue (RabbitMQ)

Secode service listen to queue and executes every incoming task

The code uses TDD and Clean Architecture principles
