# a basic setup for actix-web

execute

    sh basic_setup.sh 

to install the basic tools


and then use 

    sh make_watch.sh

to start to run your development server

after do you changes you can use to format your code:

    sh fmt.sh

to check your tests coverage

    sh coverage.sh 

to run collection of lints to catch common mistakes and improve your Rust code.

    cargo clippy --fix