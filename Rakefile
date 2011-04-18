
desc "Watch scss files and make me a server."
task :watch do
  c = Process.spawn("compass watch")
  j = Process.spawn("jekyll --auto --server")
  Process.waitpid(c)
  Process.waitpid(j)
end