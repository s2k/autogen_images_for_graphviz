
guard 'shell' do
  watch(/(.*\.gv)$/) { | m |
    dot_file = m[1]
    png_file = "#{File.basename(dot_file, '.*')}.png"
    command = "dot -Tpng -Gdpi=300 -o#{png_file} #{dot_file} && open #{png_file}"
    puts command
    puts `#{command}`
  }
end

