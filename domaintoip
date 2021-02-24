require 'resolv'

puts "Enter domain to resolve: "
domain = gets.strip

puts "\n\n"

puts "Do you want to resolve one IP address or all: (one/all)"
answer = gets.strip

if answer.downcase == "one"
	resolved = Resolv.getaddress(domain)
	puts "Resolved IP address: #{resolved}"
elsif
	resolved_all = Resolv.getaddresses(domain)
	puts "Resolved IP addresses: #{resolved_all}"
else
	puts "Wrong format. Try again"
end
