# Flaskで作ったサンプルプログラム群

## プログラム一覧
[FlaskでHello Worldを表示するプログラム](hello_world)  

formatter = logging.Formatter('%(asctime)s - %(name)s - %(levelname)s - %(message)s')
log.log
2021-08-11 15:43:13,913 - app - INFO - info:session start
2021-08-11 15:43:13,913 - app - ERROR - error:session start
2021-08-11 15:43:13,915 - app - WARNING - warn:session start
2021-08-11 15:43:13,915 - app - DEBUG - debug:session start

    app.logger.info('info:session start')
    app.logger.error('error:session start')
    app.logger.warn('warn:session start')
    app.logger.debug('debug:session start')
    
