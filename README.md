# lupmgr

## Setup

Clone this repository on the target VM:

```
git clone https://github.com/lupfoss/lupmgr.git
cd lupmgr
```

Run the following command with the value as provided by Lightup:

```
echo 'export LIGHTUP_CUSTOMER_TLA=<value>' > user_config.sh
```


From the repository folder, run the first part of the setup sequence:
```
./setup_part_one.sh
```

Communicate the public key listed and pasted at the end of `setup_part_one.sh`
to Lightup:

```
# send public key to Lightup for activation
```

After getting a go-ahead from Lightup to proceed to part two of setup, run the following:

```
./setup_part_two.sh
```

## Start

Start the agent using:

```
./connect.sh
```

## Stop

Stop the agent using:

```
./disconnect.sh
```

Stopping the agent will take away access from Lightup.


## Uninstall

Clean out the setup:

```
./uninstall.sh
```

