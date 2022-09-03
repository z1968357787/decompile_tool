# decompile_tool
this is a tool for decompile
open cmd
cd (the path of the jar)

agent-config correspond to log_agent
config correspond to log_server 

first run the log_server (java -jar log_server-0.0.4-SNAPSHOT-shaded.jar)

then run the log_agent (java -javaagent:log_agent-0.0.4-SNAPSHOT-shaded.jar -jar *.jar)(* represent your project)
