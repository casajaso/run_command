# run_command
### usage: 
    run_command.py [-h] [-c ['COMMAND' '...']] [-b [BASTIAN]] [-u [USERNAME]] [-i [IDENTITYFILE]] [-p] [hostname]

    run commands on remote host over ssh

    positional arguments:
      hostname              target hostname or ip (***required)

    optional arguments:
      -h, --help            show this help message and exit
      -c ['COMMAND' '...'], --command ['COMMAND' '...']
                            command(s) to execute on target host (***required)
                            example: -c 'command' '...' OR -c 'command; ...'
      -b [BASTIAN], --bastian [BASTIAN]
                            proxy through a bastion/jumpbox (default: None)
      -u [USERNAME], --username [USERNAME]
                            username on target host (default: jcasas)
      -i [IDENTITYFILE], --identityfile [IDENTITYFILE]
                            use ssh identify file; opens prompt (default: None)
      -p, --password        use password; opens prompt (default: no flag set)

  
