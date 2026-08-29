# ipa2026-msapp
A microservices system for automated router interface monitoring — a Scheduler reads router credentials from MongoDB and queues jobs via RabbitMQ, a Worker SSHes into each router to pull interface status, and a Flask web UI displays the results. Fully containerized with Docker Compose. Built for the IPA2026 course.
