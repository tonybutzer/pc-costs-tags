cat:
	cat Makefile


salloc:
	salloc -N 1 -n 1 -c 8 --mem-per-cpu 2048 -A impd -t 4:20:00

shell:
	srun --pty bash -i


jup:
	jupyter lab --no-browser --ip=0.0.0.0 --port=2376 --NotebookApp.token='yaml'
