send_email_message
==================

Very simple and unicode friendly way to send email message from Python code.

Usage:

    sudo pip install send_email_message
    from send_email_message import send_email_message

    email_config = dict(
        host='smtp.gmail.com',
        port=587,
        tls=True, // Or ssl=True with another port.
        user='admin@example.com',
        password='password',
        from_name='Example Site',
        # Default: encoding='utf-8'
    )

    send_email_message(to='denisr@denisr.com', subject='Example News', text='Please see http://example.com/', **email_config)

send_email_message version 0.1.0  
Copyright (C) 2013 by Denis Ryzhkov <denisr@denisr.com>  
MIT License, see http://opensource.org/licenses/MIT
