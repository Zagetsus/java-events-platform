# Roadmap

## Phase 1 — Foundation

- [ ] Define the core domain and business rules
- [ ] Initialize the Spring Boot application
- [ ] Configure the project structure
- [ ] Implement event creation
- [ ] Add unit tests

## Phase 2 — Registration

- [ ] Register participants in events
- [ ] Prevent duplicate registrations
- [ ] Enforce event capacity
- [ ] Handle registration cancellation

## Phase 3 — Waitlist

- [ ] Add participants to a waitlist when capacity is reached
- [ ] Promote participants when a spot becomes available
- [ ] Define waitlist ordering rules

## Phase 4 — Distributed workflows

- [ ] Introduce Kafka for domain events
- [ ] Add asynchronous notifications
- [ ] Introduce Redis where caching or coordination is justified

## Phase 5 — Production readiness

- [ ] Add observability
- [ ] Add integration tests
- [ ] Handle concurrency and overbooking scenarios
- [ ] Containerize the application