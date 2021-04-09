import discord
import time
from discord.ext import commands  # Import 

bot = commands.Bot(command_prefix='?')  # Prefix for your bot

# Commands for bot
@bot.event
async def on_ready():
    print(f'Logged in as {bot.user.name}')


@bot.command()
async def ping(ctx: commands.Context):
    await ctx.send('pong!')


@bot.command(name='my_name')
async def _list(ctx, af):
    await ctx.send('your name' + str(af))


@bot.command(name="gift")
async def gift(ctx):
    await ctx.send('Your OC will be deleted tomorrow')


@bot.command(name="help_me")
async def help_me(ctx):
    await ctx.send('What can i help?')
    await ctx.send('Напиши мне номер билета(На английском с маленькой буквы например: one), и я скину на него ответ')



@bot.command(name="hello")
async def hello(ctx):
    await ctx.send('Привет')
    await ctx.send('ШО')


bot.run('')#In quotes, the key for the bot
