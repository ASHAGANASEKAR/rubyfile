require 'find'
pdf_file_paths = []
Find.find('E:/asha') do |path|
  pdf_file_paths << path if path =~ /.*/
end
puts pdf_file_paths


