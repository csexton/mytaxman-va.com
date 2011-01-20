desc "Deploy"
task :deploy do
  system %{rsync -rtzh --progress --delete ./ mytaxman-va.com:mytaxman-va.com/}
end
