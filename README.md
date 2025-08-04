### Fork `@meowwolf/node-red-contrib-amqp`

# @nachyn/node-red-contrib-amqp

AMQP nodes for node-red

Changes:
- Library `amqplib` updated to version `^0.10.8`
- Added `frame_max` props for RabbitMQ 4.1

## Installation

Install via the Palette Manager or from within your node-red directory (typically `~/.node-red`) run:

```
npm i @nachyn/node-red-contrib-amqp
```

## Usage

Provides three standard nodes and an amqp broker config node.  
Please see the `Node Help` section from within node-red for more info

## Development

### Build the project

```
npm run build
```

### Run tests

```
npm test
```

Run coverage:

```
npm run test:cov
```

