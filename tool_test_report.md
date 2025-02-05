# MCP Tool Test Report

This report documents the results of testing all available MCP tools.

## Test Results Summary

| Server Name | Tool Name | Status | Notes |
|---|---|---|---|
| brave-search | brave_web_search | ✅ | Basic query test successful |
| brave-search | brave_local_search | ❌ | Rate limited (429 error) |
| google-maps | maps_geocode | ✅ | Geocoding address successful |
| google-maps | maps_reverse_geocode | ✅ | Reverse geocoding coordinates successful |
| google-maps | maps_search_places | ✅ | Place search successful |
| google-maps | maps_place_details | ✅ | Place details successful |
| google-maps | maps_distance_matrix | ✅ | Distance matrix successful |
| google-maps | maps_elevation | ✅ | Elevation data successful |
| google-maps | maps_directions | ✅ | Directions successful |
| enhanced_memory | store_memory | ✅ | Memory storage successful |
| enhanced_memory | retrieve_memory | ✅ | Memory retrieval successful |
| enhanced_memory | search_memories | ✅ | Memory search successful |
| enhanced_memory | process_memories | ✅ | Memory process successful |
| enhanced_memory | reinforce_memory | ✅ | Memory reinforce successful |
| enhanced_memory | get_memory_stats | ✅ | Memory stats retrieval successful |
| enhanced_memory | store_interaction | ✅ | Interaction storage successful |
| enhanced_memory | store_personality | ✅ | Personality storage successful |
| file_system | read_file | ✅ | File read successful |
| file_system | read_multiple_files | ✅ | Multiple files read successful |
| file_system | write_file | ✅ | File write successful |
| file_system | edit_file | ✅ | File edit test successful |
| file_system | create_directory | ✅ | Directory creation successful |
| file_system | list_directory | ✅ | Directory list successful (empty dir) |
| file_system | directory_tree | ✅ | Directory tree successful (empty dir) |
| file_system | move_file | ✅ | File move successful |
| file_system | search_files | ✅ | File search successful (no matches) |
| file_system | get_file_info | ✅ | File info retrieval successful |
| file_system | list_allowed_directories | ✅ | Allowed directories list successful |
| myqsl_server | mysql_query | ✅ | MySQL query successful |
| sequentialthinking | sequentialthinking | ✅ | Sequential thinking successful |
| alert_system | context_check | ✅ | Context check successful |
| alert_system | memory_review | ✅ | Memory review successful |
| alert_system | response_validation | ✅ | Response validation successful |
| alert_system | attention_focus | ✅ | Attention focus successful |
| crypto_market | get_listings | ✅ | Crypto listings retrieval successful |
| crypto_market | get_metadata | ✅ | Crypto metadata retrieval successful |
| crypto_market | get_quotes | ✅ | Crypto quotes retrieval successful |
| shodan | ip_lookup | ✅ | IP lookup successful |
| shodan | shodan_search | ✅ | Shodan search successful |
| shodan | cve_lookup | ✅ | CVE lookup successful |
| shodan | dns_lookup | ✅ | DNS lookup successful |
| shodan | reverse_dns_lookup | ✅ | Reverse DNS lookup successful |
| virustotal | get_url_report | ✅ | URL report retrieval successful |
| virustotal | get_url_relationship | ❌ | URL relationship retrieval failed (API error) |
| virustotal | get_file_report | ❌ | File report retrieval failed (File not found) |
| virustotal | get_file_relationship | ❌ | File relationship retrieval failed (File not found) |
| virustotal | get_ip_report | ✅ | IP report retrieval successful |
| virustotal | get_ip_relationship | ✅ | IP relationship retrieval successful |
| virustotal | get_domain_report | ✅ | Domain report retrieval successful |
| hacker-news | get_stories | ✅ | Hacker News stories retrieval successful |
| perplexity | ask_perplexity | ✅ | Perplexity ask successful |
| telegram | send_message | ✅ | Telegram message send successful |
| telegram | receive_message | ✅ | Telegram message receive successful (no message) |
| github | search_repositories | ✅ | GitHub repo search successful |
| github | create_repository | ✅ | GitHub repo creation successful |
| github | create_or_update_file | ✅ | GitHub create/update file successful |
| github | get_file_contents | ✅ | GitHub get file contents successful |
