*** About Me ***

- Distributed nature of cloud applications need infra that connects components and server,
in a loosely coupled manner to maximze scalability.
- Async messaging is widely used but also brings challenges such as the ordering of messages
poison message management, idempotency, etc.

Patterns - 

1. Async Request Reply

2. Claim Check
- Split large message into claim check and payload to avoid overwhelming message bus.

3. Choreography
- Each component of system can participate in decision making process about workflow 
of a business transaction, instead of relying in central point of control.

4. Competing Consumers
- Multiple concurrent consumers to process messages on same channel.

5. Pipes and Filters
- Break down a task into series of separate reusable elements.

6. Priority Queue

7. Publisher Subscriber
- Announce events to multiple consumers async, without coupling senders to the receviers.

8. Queue base Load Leveling
- Queue that acts as buffer between task and service, in order to smooth out intermittent
heavy loads.

9. Scheduler Agent Supervisor
- Co-ordinate a set of actions across a distributed set of services and other remote
resources.

10. Sequential Convoy
- Process a set of related messages in defined order, without blocking processing of 
other groups of messages.