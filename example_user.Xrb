class User
  attr_accessor :name, :email
  
  def initialize(attributes = {})  #sets 'User.new' params
    @name = attributes [:name]
    @email = attributes [:email]
  end
  
  def formatted_email               # define method
    "#{@name} <#{@email}>"          # String Interpolation
  end


end
