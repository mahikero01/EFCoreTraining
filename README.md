# EFCoreTraining

EF Command line:

1) get-help entityframeworkcore - show command sysntax
2) add-migration init - create a migration file name init
3) script-migration - scripts all migrations
   script-migration -idempotent - scripts all migration with if/then logic
   script-migration -from [migration] -to [migration] - controls which range of migrations scripted