exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-development}

web: bin/rails server -p $PORT -b 0.0.0.0
