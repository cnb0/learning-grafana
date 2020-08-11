


- Install, set up, and configure Grafana for real-time data analysis and visualization
- Visualize and monitor data using data sources such as InfluxDB, Prometheus, and Elasticsearch
- Explore Grafana's multi-cloud support with Microsoft Azure, Amazon CloudWatch, and Google Stackdriver

- Grafana is an open-source analytical platform used to analyze and monitoring time-series data.
- querying, visualizing, and exploring metrics and logs no matter where they are stored.

- Find out how to visualize data using Grafana
- Understand how to work with the major components of the Graph panel
- Explore mixed data sources, query inspector, and time interval settings
- Discover advanced dashboard features such as annotations, templating with variables, dashboard linking, and 
  dashboard sharing techniques
- Connect user authentication to Google, GitHub, and a variety of external services
- Find out how Grafana can provide monitoring support for cloud service infrastructures



```

Getting Started with Grafana

            Introduction to Data Visualization with Grafana
            Technical requirements
            Data and visualization
            Storing, retrieving, and visualizing data
            Why Grafana?
            Installing Grafana
            Grafana in a Docker container
            Grafana for OS X
            Homebrew
            The command line
            Grafana for Linux
            RedHat Linux
            Debian Linux
            Grafana for Windows
            Hosted Grafana on the cloud
            Connecting to the Grafana server


A Tour of the Grafana Interface
            Exploring Grafana – the Home dashboard
            Glancing at the sidebar menu
            The dashboards button&#160;
            The dashboard panels
            The dashboard settings and view mode
            Learning to use the icons on Grafana's left sidebar
            The Grafana logo
            Search
            Create
            Dashboard
            Folder
            Import
            Dashboards
            Manage
            Playlists
            Snapshots
            Explore
            Alerting
            Alert Rules
            Notification channels
            Configuration
            Data Sources
            Users
            Teams
            Plugins
            Preferences
            API Keys
            Server Admin
            Users
            Orgs
            Settings
            Stats


An Introduction to the Graph Panel
            Touring the graph panel
            Creating a simple data source
            Creating a graph panel
            Generating data series in&#160;the Query tab
            What is a query?
            Query tab features
            The Data source menu
            Query Options
            Query inspector
            Query
            Query controls
            Add Query
            Duplicating an existing query
            Editing the graph in the Panel tab
            The Settings section
            Setting the panel title and description
            The Visualisation&#160;section
            The Display&#160;section
            The Hover tooltip
            Stacking and Null value
            The Series overrides&#160;section
            The Axes&#160;section
            Left Y/Right Y
            X-axis
            The Legend&#160;section
            Options
            Values
            Hide series
            The Thresholds&#160;section
            Setting a threshold
            The Time Region&#160;section
            Setting a time region
            The Data links&#160;section
            The Links section
            The Repeat options&#160;section
            Monitoring with the Alert tab
            Rule
            Conditions
            No Data &amp; Error Handling
            Notifications


Real-World Grafana

            Connecting Grafana to a Data Source
            Technical requirements
            Installing the Prometheus server
            Installing Prometheus from Docker
            Configuring the Prometheus data source
            Exploring Prometheus
            Using Explore for investigation
            Configuring Grafana metrics
            Querying the Prometheus data source
            Typing in a metrics query
            Querying for process metrics
            Detecting trends with aggregations
            Applying aggregations to our query data
            Understanding the data source limitations
            Querying limits for series aggregations
            Querying limits for time aggregations


Visualizing Data in the Graph Panel

            Making advanced queries
            Launching server Docker containers
            Writing the ETL script
            Running the script
            Configuring the InfluxDB data source
            Understanding the time series data display
            Displaying time-aggregated data
            Debugging queries with the Query Inspector
            Observing time interval effects
            Setting the minimum interval
            Setting vertical axes
            Setting axis units
            Converting into Fahrenheit
            Autoscaling the Y axis
            Dual Y-axis display
            Graphing relative humidity
            Graphing wind chill
            Working with legends
            Setting legend contents
            Enabling legend aggregations


Visualization Panels in Grafana

                Introducing the Stat&#160;panel
                Loading the dataset
                Creating a Stat panel
                Setting the Panel tab's display
                Setting the value aggregation
                Setting Graph mode
                Setting the Field tab's standard options
                Setting units
                Setting Min and Max
                Setting the display name&#160;
                Setting the Field tab thresholds
                Setting the Field panel's value mappings
                Building our Stat panels
                Working with the Gauge panel
                Setting the Panel tab's display
                Setting the Field tab's standard options
                Setting the Field tab thresholds
                Adding a Bar Gauge panel
                Setting the Gradient mode
                Setting the Retro LCD mode
                Setting the Basic mode
                Building a bar gauge
                Geolocating data on the Worldmap panel
                Ingesting a new earthquake dataset
                Updating process_cli()
                Updating main()
                Adding dump_eq_data()
                Adding load_eq_data()
                Configuring the InfluxDB data source
                Setting up the Worldmap panel
                Structuring data fields in the Table panel&#160;
                Comparing aggregations
                Overriding field settings


Creating Your First Dashboard
                Technical requirements
                Designing a dashboard
                Conveying information
                Determining the visual context
                Prioritizing elements of importance
                Creating a high information density dashboard
                Designing the dashboard
                Building a station text panel
                Modifying the weather.py script
                Building the current conditions panel
                Building the temperature panel
                Building the moisture panel
                Building the barometer panels
                Creating a barometric pressure graph panel
                Creating a barometric pressure trend graph panel
                Building the wind panels
                Creating a wind speed graph panel
                Creating a wind direction stat panel
                Building the visibility panel
                Creating a high information visibility dashboard
                Designing the dashboard
                Building the station panel
                Building the temperature panels
                Buiding a current temperature stat panel
                Creating a high-temperature stat panel
                Creating a low-temperature stat panel
                Creating a dew point stat panel
                Building the barometer panels
                Creating a barometer reading stat panel
                Creating a barometric pressure trend stat panel
                Building the visibility panel
                Building the wind panels
                Creating a wind speed stat panel
                Creating a wind gust stat panel
                Creating a wind direction stat panel
                Building a current conditions panel


Working with Advanced Dashboard Features

            Building the data server
            Templating dashboards
            Querying with Elasticsearch
            Creating a template variable
            Adding template variables to the graph panel
            Templating additional variables
            Creating Ad hoc filters
            Repeating rows and panels with template variables
            Creating a new dashboard
            Setting up the template variables
            Configuring the panels
            Linking dashboards
            Adding dashboard tags
            Locking down a template variable
            Creating dashboard links
            Annotating dashboards
            Annotating the graph panel
            Querying tagged annotations
            Creating Elasticsearch annotation queries
            Sharing dashboards
            Sharing dashboard links
            Sharing dashboards by exporting
            Sharing dashboard snapshots


Grafana Alerting

            Setting thresholds
            Capturing real-time data
            Processing the Logstash input
            Filtering the Logstash events
            Outputting the data
            Creating an ElasticSearch data source
            Building the dashboard panels
            Setting thresholds
            Constraining thresholds to time regions
            Configuring alerts
            Alert rules
            Conditions
            Handling edge cases
            Assigning alerts to notification channels
            Setting up an email notification channel
            Configuring Grafana Docker containers
            Troubleshooting and controlling alerts
            Checking the alert history
            Testing the rule
            Controlling alerts

Exploring Logs with Grafana Loki
            Loading system logs into Loki
            Visualizing Loki log data with Explore
            Adding additional service logs
            Querying logs and metrics with Explore


Managing Grafana

            Organizing Dashboards
            Technical requirements
            Managing dashboards and folders
            Naming a dashboard
            Dashboard naming tips
            Working with dashboard folders
            Creating a dashboard folder
            Adding dashboards to a folder
            Deleting folders
            Guiding dashboard folder management
            Starring and tagging dashboards
            Marking dashboards as favorites
            Tagging dashboards
            Adding tags
            Deleting tags
            Building and running dashboard playlists
            Creating a playlist
            Displaying a playlist
            Displaying playlists in normal mode
            Displaying playlists in TV mode
            Displaying playlists in Kiosk mode
            Displaying playlists with auto fit panels
            Editing a playlist
            Exploring the dashboard list panel
            Setting dashboard list panel options

Managing Permissions for Users and Teams
            Technical requirements
            Understanding key permissions concepts
            Organizations
            Users
            Roles
            Teams
            Adding users
            Adding users&#160;–&#160;by invitation only
            Adding users –&#160;serve yourself
            Setting permissions
            Setting organization roles
            Setting folder permissions
            Setting dashboard permissions
            Establishing teams
            Setting up a team
            Team members
            Team settings
            Permission rules
            Administering users and organizations
            Managing users
            Disabling or deleting a user
            Elevating a user to Super Admin
            Setting user organizations
            Organization admin and Super Admin roles
            Managing organizations
            Creating a new organization
            Renaming and setting the organization preferences
            Switching between organizations


Authentication with External Services
            Technical requirements
            Authenticating with OpenLDAP
            Setting up an OpenLDAP server
            Configuring Grafana to use LDAP
            Testing the Grafana configuration
            Adding a user to OpenLDAP
            Looking up a user in Grafana
            Authenticating with GitHub
            Authenticating with Google
            Authenticating with Okta


Cloud Monitoring
            Configuring an AWS CloudWatch data source
            Creating the policy
            Creating the user
            Configure the new data source
            Configuring a Microsoft Azure Monitor data source
            Registering the Grafana application
            Setting the application role
            Generating application Secrets
            Configuring the Azure Monitor data source
            Configuring Azure Log Analytics
            Generating the API key for Application Insights Details
            Configuring a Google Stackdriver data source
            Enabling Google Cloud APIs
            Creating a Google Service Account
            Configuring a Google Stackdriver data source