# Soar-with-Deno


curl -i -XPOST -d '{"username": "mohitahlawat", "password": "123"}' --url http://127.0.0.1:5555/register 

curl -i -XPOST -d '{"username": "mohitahlawat", "password": "123"}' --url http://127.0.0.1:5555/login --cookie-jar cookie.cookie


curl -i -XPUT -d '{"username": "mohitahlawat-Ready-For-Submission", "password": "123"}' --url http://127.0.0.1:5555/auth/update --cookie cookie.cookie -H "Authorization: Bearer eyJhbGciOiJIUzUxMiIsInR5cGUiOiJKV1QifQ.eyJleHAiOjE3NjQzOTk5MzAsImF1ZCI6Imh0dHA6Ly8xMjcuMC4wLjE6NTU1NSIsInVzZXIiOiJtb2hpdGFobGF3YXQifQ.I3sdVlqKQrIeZMRXoPlGE5sfcDQRwi90ERB2KVUgUnTA5Sz90DH7vr8FLnKZrIRF_b7ECQSlH_msOfzSQDq6ng"

curl -i -XPOST -d '{"username": "mohitahlawat-Ready-For-Submission", "password": "123"}' --url http://127.0.0.1:5555/login --cookie-jar cookie.cookie


curl -i -XDELETE --url "http://127.0.0.1:5555/auth/delete" --cookie cookie.cookie -H "Authorization: Bearer eyJhbGciOiJIUzUxMiIsInR5cGUiOiJKV1QifQ.eyJleHAiOjE3NjQ0MDAxNzUsImF1ZCI6Imh0dHA6Ly8xMjcuMC4wLjE6NTU1NSIsInVzZXIiOiJtb2hpdGFobGF3YXQtUmVhZHktRm9yLVN1Ym1pc3Npb24ifQ.bgXNAiNUn6h0UH5TdiHhSPtmcykLSttfAmzsTXaehzclP_2rNrIaZ9o-K-6x-z0_olv65PWUZRhcw8s_keFhWA"
