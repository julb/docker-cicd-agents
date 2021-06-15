# Disable useless tasks.
#Rake::Task['release'].clear
#Rake::Task['install:local'].clear
#Rake::Task['install'].clear

desc 'Create an application AMI with Packer'
task :build do
  sh "packer build base-rhel8.json"
end
